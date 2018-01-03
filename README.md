# yellowpaper

[![Gitter](https://badges.gitter.im/ethereum/yellowpaper.svg)](https://gitter.im/ethereum/yellowpaper?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Notice that this is not up-to-date

This Yellow Paper does not include changes to Ethereum that have been made after [this commit, 759dcc, (after which this repository was branched from the Ethereum Foundation Yellow Paper repository, i.e. the latest shared commit in both repositories is this commit) on August 8 2017](https://github.com/jamesray1/yellowpaper/commit/759dccde49c3a1a457196665d1db06baba220bf0). See the ensuing discussion [here](https://gitter.im/ethereum/yellowpaper?at=5a4ad08e03838b2f2a5d350f) to gain a better understanding of why the Yellow paper won't be maintained by the Ethereum Foundation. In short, it is because of using the KEVM, "the first fully executable formal semantics of the EVM", as an alternative to the current EVM (as of January 4 2018), which is reasonable.

For the Byzantium Hard Fork (of which the changes made by it are not included in this paper), refer to [here](https://web.archive.org/web/20171026151615/https://github.com/ethereum/EIPs#accepted-eips-planned-for-adoption-in-the-byzantium-metropolis-hard-fork), which is an archive link showing the Byzantium EIPs. For further changes, e.g. the Constantinople Hard Fork (TBA) and Serenity, refer to the [the finalized list of EIPs in the Ethereum EIPs repository](https://github.com/ethereum/EIPS#finalized-eips-standards-that-have-been-adopted). Note that [this is an archive link in case the EIPs list is changed in a way that does not breakdown EIPs into different releases, as is the case up until now. This archive link lists the deferred Constantinople EIPs](https://web.archive.org/web/20180103233351/https://github.com/ethereum/EIPS). For changes in the Homestead release, see [this EIP](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2.md).

## The paper
The paper comes as a single ``latex`` file ``Paper.tex``. 

Here is the latest version of the PDF that is based on the changes that I've made:

[Paper.pdf](https://github.com/ethereum/yellowpaper/files/1596574/Paper.pdf).

This version of the yellow paper can be used to get links that direct to specific info in the yellow paper, which is useful e.g. for pedagogical and academic purposes. [Here](
https://github.com/ethereum/yellowpaper/files/1596574/Paper.pdf#blockhash) is an example of such a use. To get this link you just right click on a link that directs to the target that you want in the PDF (in a browser or program) and copy the link.

How to build
---
In order to build, use the supplied build script (``build.sh``. You can clone the directory with `git clone https://github.com/ethereum/yellowpaper.git` or use the URL of your forked clone, then `cd yellowpaper` and run `./build.sh`. Then open the produced PDF. If running `./build.sh` again, you can leave the PDF open; you don't need to close and reopen it for it to update). Following the first time, you can use the standard `pdflatex` tools like http://latex.informatik.uni-halle.de/latex-online/latex.php for compiling/preview. It can be viewed in ``PDF`` format after building.
