Distributions.jl Release Notes
================================

**Note:** We reached a relatively stable API at version *0.5.0*, and have maintained release notes since then.

Changes from v0.5 to v0.6
---------------------------

* Some bug fixes
* Add `CategoricalDirectSampler`.
* Add univariate von Mises distribution ([#223])
* Add Fréchet distribution ([#238])
* Add noncentral hypergeometric distribution ([#255])
* More functions for hypergeometric distribution (``support``, ``mode``, ``kurtosis``, ``skewness``, etc) ([#256])
* More efficient algorithm to sample from truncated distributions. ([#243])
* Various updates to make it work with both Julia 0.3 and 0.4 
* Improved implementation of ``show``. ([#290])
* A consistent testing framework for univariate distributions ([#291])
* Reimplement truncated distributions, fixing various bugs ([#295])
* Refactored type system for multivariate normal distributions, supporting zero-mean normal seamlessly and introducing common constructors. ([#296])

[#238]: https://github.com/JuliaStats/Distributions.jl/pull/238
[#223]: https://github.com/JuliaStats/Distributions.jl/pull/223
[#243]: https://github.com/JuliaStats/Distributions.jl/pull/243
[#255]: https://github.com/JuliaStats/Distributions.jl/pull/255
[#256]: https://github.com/JuliaStats/Distributions.jl/pull/256
[#290]: https://github.com/JuliaStats/Distributions.jl/pull/290
[#291]: https://github.com/JuliaStats/Distributions.jl/pull/291
[#295]: https://github.com/JuliaStats/Distributions.jl/pull/295
[#296]: https://github.com/JuliaStats/Distributions.jl/pull/296
