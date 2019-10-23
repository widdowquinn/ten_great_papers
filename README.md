# Ten great papers for biologists starting out in computational biology

## Why are you even doing this?

The PLoS journals regularly produce papers with good general advice for researchers under a "Ten simple rules for X", or "A Quick Y to Z". They're always good quick reads, and I don't think there's one that I haven't learned something from.

That there are so many of these papers makes it difficult to recommend any single one, or even a small number. But under the same constraint as those papers' authors, here are ten of the most appropriate that I put together for wet lab biologists looking for general guidance when turning to bioinformatics and computing more seriously. I've had to leave some great papers out, but suggestions are what the [issues page](https://github.com/widdowquinn/ten_great_papers/issues) of this repository is for ;)

## The papers

- NOTE: PDFs of all the papers can be found in the `papers` subdirectory of this repository (Which you can download as a compressed file [here](https://github.com/widdowquinn/ten_great_papers/releases)).

1. Noble, W. S. (2009). A quick guide to organizing computational biology projects. *PLoS Computational Biology*, 5(7), e1000424. [http://doi.org/10.1371/journal.pcbi.1000424](http://doi.org/10.1371/journal.pcbi.1000424)

    The classic guide to structured organisation of files for a computational project. It's absolutely foundational that you will need to be able to rapidly and unambiguously find your data (and code, if you write any) quickly, and that others will be able to follow your work and your reasoning. This paper presents a sensible way to begin doing that. It's natural to move away from the precise structure described here, over time, to suit the project and what works for you - buts if you don't take into account the principles described in this paper, you *will* have a bad time at some point.

2. Sandve, G. K., Nekrutenko, A., Taylor, J., & Hovig, E. (2013). Ten simple rules for reproducible computational research. *PLoS Computational Biology*, 9(10), e1003285. [http://doi.org/10.1371/journal.pcbi.1003285](http://doi.org/10.1371/journal.pcbi.1003285)

    No matter the topic of your research, there are general principles over and above filesystem organisation that will help keep your data in good shape and *reproducible* - both by yourself and others. That can seem like a luxury, when you're starting a project, but when the stranger who needs to understand what you've done and how is *you* in six months' time, you will thank your previous self. This is a good guide to read in association with the Noble paper, as applying the techniques from the two will make your life much easier for small projects, and will make large projects achievable.

3. Hart, E. M., Barmby, P., LeBauer, D., Michonneau, F., Mount, S., Mulrooney, P., et al. (2016). Ten Simple Rules for Digital Data Storage. *PLoS Computational Biology*, 12(10), e1005097. [http://doi.org/10.1371/journal.pcbi.1005097](http://doi.org/10.1371/journal.pcbi.1005097)

    Your data is everything with a computational project. If it disappears, then your project does, too (so make sure you have multiple backups on multiple sites). The technicalities of ensuring data integrity in the short and long term aren't often emphasised on undergraduate (or postgraduate) courses, but in the ever more computational world of biology, developing these skills might one day rescue hundreds of thousands of pounds worth of sunk costs. And a career or two. In the meantime, even for small projects, they will give you peace of mind.

4. Schnell, S. (2015). Ten Simple Rules for a Computational Biologist's Laboratory Notebook. *PLoS Computational Biology*, 11(9), e1004385. [http://doi.org/10.1371/journal.pcbi.1004385](http://doi.org/10.1371/journal.pcbi.1004385)

    In addition to storing the data, analyses (and maybe code) you produce - a laboratory notebook recording thoughts and processes is essential. Sometimes it's also required legally. This is another good paper to read alongside Noble and Sandve *et al.*, as it complements the more technical approaches outlined in those papers.

5. Kass, R. E., Caffo, B. S., Davidian, M., Meng, X.-L., Yu, B., & Reid, N. (2016). Ten Simple Rules for Effective Statistical Practice. *PLoS Computational Biology*, 12(6), e1004961. [http://doi.org/10.1371/journal.pcbi.1004961](http://doi.org/10.1371/journal.pcbi.1004961)

    Computational biology often means that there's an awful lot of data, which means that there's also often a similarly large amount of accompanying statistical work. This paper describes some general approaches to data management and processing (see also Hart *et al.*) that will help make your analyses run more smoothly.

6. Carey, M. A., Papin, J. A. (2018) Ten simple rules for biologists learning to program. *PLOS Computational Biology* 14(1): e1005871. [https://doi.org/10.1371/journal.pcbi.1005871](https://doi.org/10.1371/journal.pcbi.1005871)

     You are likely, in nearly all computational biology projects, to need to program, and maybe even *learn* to program. This paper gives excellent practical advice on learning how to program. It covers general strategies for programming, pros and cons of programming languages, and leads into the Wilson *et al.* and other papers below in a sensible way.

7. Wilson, G., Aruliah, D. A., Brown, C. T., Chue Hong, N. P., Davis, M., Guy, R. T., et al. (2014). Best Practices for Scientific Computing,*PLoS Biology* 12(1), e1001745–2. [http://doi.org/10.1371/journal.pbio.1001745](http://doi.org/10.1371/journal.pbio.1001745)

    If you reach a stage where you are writing your own software (this can happen quite early on any project!) you will benefit from keeping in mind general best practices of software engineering. These play a similar role to aseptic technique in a microbiology lab. They will help you keep your code "uncontaminated" and "clean," and save you from unnecessary extra work fixing problems, later. There's no substitute for training, but while you're waiting for that oversubscribed [Carpentries](https://carpentries.org/) course to have a space (they're worth waiting for, by the way!), there's this to read.

8. Blischak, J. D., Davenport, E. R., & Wilson, G. (2016). A Quick Introduction to Version Control with Git and GitHub. *PLoS Computational Biology*, 12(1), e1004668. [http://doi.org/10.1371/journal.pcbi.1004668](http://doi.org/10.1371/journal.pcbi.1004668)

    The Wilson *et al.* paper describes a broad set of software engineering principles, but one principle in particular benefits from the extra detail of this article. Version control will help enable you to keep any code or scripts you write, *and any other computational data or activity* backed up, reproducible and well-organised. It's a quite technical topic, especially coming from biology, but once understood it will pay you back many times over.

9. Perez-Riverol, Y., Gatto, L., Wang, R., Sachsenberg, T., Uszkoreit, J, *et al.* (2016) Ten Simple Rules for Taking Advantage of Git and GitHub. *PLOS Computational Biology* 12(7): e1004947. [https://doi.org/10.1371/journal.pcbi.1004947](https://doi.org/10.1371/journal.pcbi.1004947)

    This paper covers some of the same ground as the Blischak paper above, regarding `git`, but it's such a central tool for managing and sharing scripts, analyses, and research software that it's worth emphasising again. This paper takes some of the deliberately technical aspects of the Blischak *et al.* paper, and extends them to broader applications, like project management,  and encouraging collegiality and community-building *via* GitHub.

10. Weinberger, C. J., Evans, J. A., & Allesina, S. (2015). Ten simple (empirical) rules for writing science. *PLoS Computational Biology*, 11(4), e1004205. [http://doi.org/10.1371/journal.pcbi.1004205](http://doi.org/10.1371/journal.pcbi.1004205)

    At some point, you'll want to describe your work to others. Writing about computational biology is writing about biology. It might be tempting, with a new field, to go into more detail to demonstrate your own understanding, or just because it seems a bit unfamiliar or potentially complex/jargon-ridden to your peers who haven't made the same journey. But the general principles of scientific writing still apply, and this paper does an excellent (and concise) job of encouraging and demonstrating good scientific writing.

- BONUS PAPER: Erren, T. C., Slanger, T. E., Groß, J. V., Bourne, P. E., & Cullen, P. (2015). Ten simple rules for lifelong learning, according to Hamming. *PLoS Computational Biology*, 11(2), e1004020. [http://doi.org/10.1371/journal.pcbi.1004020](http://doi.org/10.1371/journal.pcbi.1004020)

    This is a really good set of points giving general advice on how to keep an open, receptive mind. This doesn't just aid lifelong learning, but helps keep life interesting.
