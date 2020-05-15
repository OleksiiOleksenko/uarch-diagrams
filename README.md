This repository contains detailed microarchitectural diagrams of CPUs. Inspired by wikichip.org . The information is based on vendor documentation and pattens, as well as on published reverse engineering efforts of the researchers in the field.

The diagrams are created manually and based on many sources. Therefore, they most likely contain mistakes. If you find one, please, open an issue or, even better, create a pull request.

# Current Progress

So far, I just started working on this project. The only diagram present is Skylake client uarch, and even it is not finished. For example, MMU has no details at all and Front End would need many more loving touches.

# References

* wikichip.org
* https://www.agner.org/optimize/
* Baer, Jean-Loup. Microprocessor architecture: from simple pipelines to chip multiprocessors. 2009.
* Krste Asanović. Lecture Slides of CS152 Computer Architecture and Engineering
* Hennessy, John L., and A. David. Patterson . Computer Architecture: A Quantitative Approach. Sixth Edition. 2017


# Load Buffer
* Schwarz, Michael, et al. "ZombieLoad: Cross-privilege-boundary data sampling." Proceedings of the 2019 ACM SIGSAC Conference on Computer and Communications Security. 2019.
* Abramson, Jeffery M., et al. "Method and apparatus for performing a store operation." U.S. Patent No. 6,378,062. 1997

# Store Buffer
* Abramson, Jeffrey M., et al. "Method and apparatus for dispatching and executing a load operation to memory." U.S. Patent No. 5,717,882. 10 Feb. 1998.