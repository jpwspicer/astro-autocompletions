Astronomical & Mathematical Symbols for Sublime Text 2/3
==================================

This package Provides auto-completion for unicode astronomical and mathematical symbols in Sublime Text 2/3. It includes celestial symbols (⨁, ♂, ☉, ♃, etc.), Greek letters (α, Γ, Ω, ω, etc.), vector notation (g⃗, f⃗, β⃗, Ω⃗, etc.), dot- and double-dot derivative notation (ȧ, Q̇, μ̈, ϕ̈, etc.), super- and subscripts ( ₀, ₂, ², ⁵, etc.), and various other symbols (⨯, ω̃, ÷, °, ∛, etc.). Just enter a the name of the desired symbol and press `<tab>`.


Examples
--------

| Entered Text     |  Result  |
| :-------------   | :------: |
| `earth<tab>`     |   `⨁`    |
| `muearth<tab>`   |   `μ⨁`   |
| `remoon<tab>`    |   `R☾`   |
| `sun<tab>`       |   `☉`    |
| `omegatilde<tab>`|   `ω̃`    |
| `hvec<tab>`	   |   `h⃗`    |
| `Rvec<tab>`      |   `R⃗`    |
| `omegadot<tab>`  |   `ω̇`    |
| `eddot<tab>`     |   `ë`    |
| `f_0<tab>`       |   `f₀`   |




Installation
------------


### Package Control

You can install this package manually by installing Package Control, press `<Ctrl+Shift+P>`, choose `Package Control: Add Repository` from the list and type in [https://github.com/jpwspicer/sublime-astro-symbols.git][2].

Then press `<Ctrl+Shift+P>`, choose `Package Control: Install Package`from the list and search for `AstroSymbols`.

If that doesn't work, press `<Ctrl+Shift+P>`, choose `Package Control: Advanced Install Package`from the list and type in `sublime-astro-symbols`.

### Git Clone

Clone this repository in to the Sublime Text 2/3 `Packages` directory, which is located whereever the _Preferences_ → _Browse Packages_ option in Sublime.

### Git Copy

Alternately, you can download a [copy of this package][3], rename the file to `AstroSymbols.sublime-package` and move it to the `Installed Packages` directory which is located in the same directory as the `Packages` directory. Afterwards, restart Sublime and you're done.

[1]: https://packagecontrol.io/ "Package Control"
[2]: https://github.com/jpwspicer/sublime-astro-symbols.git "Astro Symbols on GitHub"
[3]: https://github.com/jpwspicer/sublime-astro-symbols/archive/master.zip "ZIP-Archive of Astro Symbols"

Complete Auto-Completion List
-----------------------------


| Entered Text     |  Result after <tab>|
| :-------------   | :------: 			|
| `alpha` 		   |   `α`    			|
| `beta` 		   |   `β`    			|
| `gamma` 		   |   `γ`    			|
| `delta` 		   |   `δ`    			|
| `epsilon` 	   |   `ε`    			|
| `zeta` 		   |   `ζ`    			|
| `eta` 		   |   `η`    			|
| `theta` 		   |   `θ`    			|
| `iota` 		   |   `ι`    			|
| `kappa` 		   |   `κ`    			|
| `lambda` 		   |   `λ`    			|
| `lamda` 		   |   `λ`    			|
| `mu` 			   |   `μ`    			|
| `nu` 			   |   `ν`    			|
| `xi` 			   |   `ξ`    			|
| `omicron` 	   |   `ο`    			|
| `pi` 			   |   `π`    			|
| `rho` 		   |   `ρ`    			|
| `sigma` 		   |   `σ`    			|
| `tau` 		   |   `τ`    			|
| `upsilon` 	   |   `υ`    			|
| `phi` 		   |   `ϕ`    			|
| `chi` 		   |   `χ`    			|
| `psi` 		   |   `ψ`    			|
| `omega` 		   |   `ω`    			|

Capital Greek letters
| `Alpha` 		   |   `Α`    			|

		{ "trigger": "Alpha`		"contents": "Α`	},
		{ "trigger": "Beta`		"contents": "Β`	},
		{ "trigger": "Gamma`		"contents": "Γ`	},
		{ "trigger": "Delta`		"contents": "Δ`	},
		{ "trigger": "Epsilon`		"contents": "Ε`	},
		{ "trigger": "Zeta`		"contents": "Ζ`	},
		{ "trigger": "Eta`			"contents": "Η`	},
		{ "trigger": "Theta` 		"contents": "Θ`	},
		{ "trigger": "Iota` 		"contents": "Ι`	},
		{ "trigger": "Kappa` 		"contents": "Κ`	},
		{ "trigger": "Lambda` 		"contents": "Λ`	},
		{ "trigger": "Lamda` 		"contents": "Λ`	},
		{ "trigger": "Mu` 			"contents": "Μ`	},
		{ "trigger": "Nu` 			"contents": "Ν`	},
		{ "trigger": "Xi`	 		"contents": "Ξ`	},
		{ "trigger": "Omicron`		"contents": "Ο`	},
		{ "trigger": "Pi` 			"contents": "Π`	},
		{ "trigger": "Rho` 		"contents": "Ρ`	},
		{ "trigger": "Sigma` 		"contents": "Σ`	},
		{ "trigger": "Tau` 		"contents": "Τ`	},
		{ "trigger": "Upsilon` 	"contents": "Υ`	},
		{ "trigger": "Phi` 		"contents": "Φ`	},
		{ "trigger": "Chi` 		"contents": "Χ`	},
		{ "trigger": "Psi` 		"contents": "Ψ`	},
		{ "trigger": "Omega` 		"contents": "Ω`	},

// Vectors - Lowercase Roman letters
		{ "trigger": "avec`		"contents": "a⃗` 	},
		{ "trigger": "bvec`		"contents": "b⃗` 	},
		{ "trigger": "cvec`		"contents": "c⃗` 	},
		{ "trigger": "dvec`		"contents": "d⃗` 	},
		{ "trigger": "evec`		"contents": "e⃗` 	},
		{ "trigger": "fvec`		"contents": "f⃗` 	},
		{ "trigger": "gvec`		"contents": "g⃗` 	},
		{ "trigger": "hvec`		"contents": "h⃗` 	},
		{ "trigger": "ivec`		"contents": "i⃗` 	},
		{ "trigger": "jvec`		"contents": "j⃗` 	},
		{ "trigger": "kvec`		"contents": "k⃗` 	},
		{ "trigger": "lvec`		"contents": "l⃗` 	},
		{ "trigger": "mvec`		"contents": "m⃗` 	},
		{ "trigger": "nvec`		"contents": "n⃗` 	},
		{ "trigger": "ovec`		"contents": "o⃗` 	},
		{ "trigger": "pvec`		"contents": "p⃗` 	},
		{ "trigger": "qvec`		"contents": "q⃗` 	},
		{ "trigger": "rvec`		"contents": "r⃗` 	},
		{ "trigger": "svec`		"contents": "s⃗` 	},
		{ "trigger": "tvec`		"contents": "t⃗` 	},
		{ "trigger": "uvec`		"contents": "u⃗` 	},
		{ "trigger": "vvec`		"contents": "v⃗` 	},
		{ "trigger": "wvec`		"contents": "w⃗` 	},
		{ "trigger": "xvec`		"contents": "x⃗` 	},
		{ "trigger": "yvec`		"contents": "y⃗` 	},
		{ "trigger": "zvec`		"contents": "z⃗` 	},

// Vectors - Uppercase Roman letters
		{ "trigger": "Avec`		"contents": "A⃗` 	},
		{ "trigger": "Bvec`		"contents": "B⃗` 	},
		{ "trigger": "Cvec`		"contents": "C⃗` 	},
		{ "trigger": "Dvec`		"contents": "D⃗` 	},
		{ "trigger": "Evec`		"contents": "E⃗` 	},
		{ "trigger": "Fvec`		"contents": "F⃗` 	},
		{ "trigger": "Gvec`		"contents": "G⃗` 	},
		{ "trigger": "Hvec`		"contents": "H⃗` 	},
		{ "trigger": "Ivec`		"contents": "I⃗` 	},
		{ "trigger": "Jvec`		"contents": "J⃗` 	},
		{ "trigger": "Kvec`		"contents": "K⃗` 	},
		{ "trigger": "Lvec`		"contents": "L⃗` 	},
		{ "trigger": "Mvec`		"contents": "M⃗` 	},
		{ "trigger": "Nvec`		"contents": "N⃗` 	},
		{ "trigger": "Ovec`		"contents": "O⃗` 	},
		{ "trigger": "Pvec`		"contents": "P⃗` 	},
		{ "trigger": "Qvec`		"contents": "Q⃗` 	},
		{ "trigger": "Rvec`		"contents": "R⃗` 	},
		{ "trigger": "Svec`		"contents": "S⃗` 	},
		{ "trigger": "Tvec`		"contents": "T⃗` 	},
		{ "trigger": "Uvec`		"contents": "U⃗` 	},
		{ "trigger": "Vvec`		"contents": "V⃗` 	},
		{ "trigger": "Wvec`		"contents": "W⃗` 	},
		{ "trigger": "Xvec`		"contents": "X⃗` 	},
		{ "trigger": "Yvec`		"contents": "Y⃗` 	},
		{ "trigger": "Zvec`		"contents": "Z⃗` 	},

// Vectors - Lowercase Greek letters
		{ "trigger": "alphavec`	"contents": "α⃗` 	},
		{ "trigger": "betavec`		"contents": "β⃗` 	},
		{ "trigger": "gammavec`	"contents": "γ⃗` 	},
		{ "trigger": "deltavec`	"contents": "δ⃗` 	},
		{ "trigger": "epsilonvec`	"contents": "ε⃗` 	},
		{ "trigger": "zetavec`		"contents": "ζ⃗` 	},
		{ "trigger": "etavec`		"contents": "η⃗` 	},
		{ "trigger": "thetavec`	"contents": "θ⃗` 	},
		{ "trigger": "iotavec`		"contents": "ι⃗` 	},
		{ "trigger": "kappavec`	"contents": "κ⃗` 	},
		{ "trigger": "lambdavec`	"contents": "λ⃗` 	},
		{ "trigger": "lamdavec`	"contents": "λ⃗` 	},
		{ "trigger": "muvec`		"contents": "μ⃗` 	},
		{ "trigger": "nuvec`		"contents": "ν⃗` 	},
		{ "trigger": "xivec`		"contents": "ξ⃗` 	},
		{ "trigger": "omicronvec`	"contents": "ο⃗` 	},
		{ "trigger": "pivec`		"contents": "π⃗` 	},
		{ "trigger": "rhovec`		"contents": "ρ⃗` 	},
		{ "trigger": "sigmavec`	"contents": "σ⃗` 	},
		{ "trigger": "tauvec`		"contents": "τ⃗` 	},
		{ "trigger": "upsilonvec`	"contents": "υ⃗` 	},
		{ "trigger": "phivec`		"contents": "ϕ⃗` 	},
		{ "trigger": "chivec`		"contents": "χ⃗` 	},
		{ "trigger": "psivec`		"contents": "ψ⃗` 	},
		{ "trigger": "omegavec`	"contents": "ω⃗` 	},

// Vectors - Uppercase Greek letters
		{ "trigger": "Alphavec`	"contents": "Α⃗` 	},
		{ "trigger": "Betavec`		"contents": "Β⃗` 	},
		{ "trigger": "Gammavec`	"contents": "Γ⃗` 	},
		{ "trigger": "Deltavec`	"contents": "Δ⃗` 	},
		{ "trigger": "Epsilonvec`	"contents": "Ε⃗` 	},
		{ "trigger": "Zetavec`		"contents": "Ζ⃗` 	},
		{ "trigger": "Etavec`		"contents": "Η⃗` 	},
		{ "trigger": "Thetavec`	"contents": "Θ⃗` 	},
		{ "trigger": "Iotavec`		"contents": "Ι⃗` 	},
		{ "trigger": "Kappavec`	"contents": "Κ⃗` 	},
		{ "trigger": "Lambdavec`	"contents": "Λ⃗` 	},
		{ "trigger": "Lamdavec`	"contents": "Λ⃗` 	},
		{ "trigger": "Muvec`		"contents": "Μ⃗` 	},
		{ "trigger": "Nuvec`		"contents": "Ν⃗` 	},
		{ "trigger": "Xivec`		"contents": "Ξ⃗` 	},
		{ "trigger": "Omicronvec`	"contents": "Ο⃗` 	},
		{ "trigger": "Pivec`		"contents": "Π⃗` 	},
		{ "trigger": "Rhovec`		"contents": "Ρ⃗` 	},
		{ "trigger": "Sigmavec`	"contents": "Σ⃗` 	},
		{ "trigger": "Tauvec`		"contents": "Τ⃗` 	},
		{ "trigger": "Upsilonvec`	"contents": "Υ⃗` 	},
		{ "trigger": "Phivec`		"contents": "Φ⃗` 	},
		{ "trigger": "Chivec`		"contents": "Χ⃗` 	},
		{ "trigger": "Psivec`		"contents": "Ψ⃗` 	},
		{ "trigger": "Omegavec`	"contents": "Ω⃗` 	},

// Dot Derivatives - Lowercase Roman letters
		{ "trigger": "adot`		"contents": "ȧ` 	},
		{ "trigger": "bdot`		"contents": "ḃ` 	},
		{ "trigger": "cdot`		"contents": "ċ` 	},
		{ "trigger": "ddot`		"contents": "ḋ` 	},
		{ "trigger": "edot`		"contents": "ė` 	},
		{ "trigger": "fdot`		"contents": "ḟ` 	},
		{ "trigger": "gdot`		"contents": "ġ` 	},
		{ "trigger": "hdot`		"contents": "ḣ` 	},
		{ "trigger": "idot`		"contents": "i̇` 	},
		{ "trigger": "jdot`		"contents": "j̇` 	},
		{ "trigger": "kdot`		"contents": "k̇` 	},
		{ "trigger": "ldot`		"contents": "l̇` 	},
		{ "trigger": "mdot`		"contents": "ṁ` 	},
		{ "trigger": "ndot`		"contents": "ṅ` 	},
		{ "trigger": "odot`		"contents": "ȯ` 	},
		{ "trigger": "pdot`		"contents": "ṗ` 	},
		{ "trigger": "qdot`		"contents": "q̇` 	},
		{ "trigger": "rdot`		"contents": "ṙ` 	},
		{ "trigger": "sdot`		"contents": "ṡ` 	},
		{ "trigger": "tdot`		"contents": "ṫ` 	},
		{ "trigger": "udot`		"contents": "u̇` 	},
		{ "trigger": "vdot`		"contents": "v̇` 	},
		{ "trigger": "wdot`		"contents": "ẇ` 	},
		{ "trigger": "xdot`		"contents": "ẋ` 	},
		{ "trigger": "ydot`		"contents": "ẏ` 	},
		{ "trigger": "zdot`		"contents": "ż` 	},

// Dot Derivatives - Uppercase Roman letters
		{ "trigger": "Adot`		"contents": "Ȧ` 	},
		{ "trigger": "Bdot`		"contents": "Ḃ` 	},
		{ "trigger": "Cdot`		"contents": "Ċ` 	},
		{ "trigger": "Ddot`		"contents": "Ḋ` 	},
		{ "trigger": "Edot`		"contents": "Ė` 	},
		{ "trigger": "Fdot`		"contents": "Ḟ` 	},
		{ "trigger": "Gdot`		"contents": "Ġ` 	},
		{ "trigger": "Hdot`		"contents": "Ḣ` 	},
		{ "trigger": "Idot`		"contents": "İ` 	},
		{ "trigger": "Jdot`		"contents": "J̇` 	},
		{ "trigger": "Kdot`		"contents": "K̇` 	},
		{ "trigger": "Ldot`		"contents": "L̇` 	},
		{ "trigger": "Mdot`		"contents": "Ṁ` 	},
		{ "trigger": "Ndot`		"contents": "Ṅ` 	},
		{ "trigger": "Odot`		"contents": "Ȯ` 	},
		{ "trigger": "Pdot`		"contents": "Ṗ` 	},
		{ "trigger": "Qdot`		"contents": "Q̇` 	},
		{ "trigger": "Rdot`		"contents": "Ṙ` 	},
		{ "trigger": "Sdot`		"contents": "Ṡ` 	},
		{ "trigger": "Tdot`		"contents": "Ṫ` 	},
		{ "trigger": "Udot`		"contents": "U̇` 	},
		{ "trigger": "Vdot`		"contents": "V̇` 	},
		{ "trigger": "Wdot`		"contents": "Ẇ` 	},
		{ "trigger": "Xdot`		"contents": "Ẋ` 	},
		{ "trigger": "Ydot`		"contents": "Ẏ` 	},
		{ "trigger": "Zdot`		"contents": "Ż` 	},

// Dot Derivatives - Lowercase Greek letters
		{ "trigger": "alphadot`	"contents": "α̇` 	},
		{ "trigger": "betadot`		"contents": "β̇` 	},
		{ "trigger": "gammadot`	"contents": "γ̇` 	},
		{ "trigger": "deltadot`	"contents": "δ̇` 	},
		{ "trigger": "epsilondot`	"contents": "ε̇` 	},
		{ "trigger": "zetadot`		"contents": "ζ̇` 	},
		{ "trigger": "etadot`		"contents": "η̇` 	},
		{ "trigger": "thetadot`	"contents": "θ̇` 	},
		{ "trigger": "iotadot`		"contents": "ι̇` 	},
		{ "trigger": "kappadot`	"contents": "κ̇` 	},
		{ "trigger": "lambdadot`	"contents": "λ̇` 	},
		{ "trigger": "lamdadot`	"contents": "λ̇` 	},
		{ "trigger": "mudot`		"contents": "μ̇` 	},
		{ "trigger": "nudot`		"contents": "ν̇` 	},
		{ "trigger": "xidot`		"contents": "ξ̇` 	},
		{ "trigger": "omicrondot`	"contents": "ο̇` 	},
		{ "trigger": "pidot`		"contents": "π̇` 	},
		{ "trigger": "rhodot`		"contents": "ρ̇` 	},
		{ "trigger": "sigmadot`	"contents": "σ̇` 	},
		{ "trigger": "taudot`		"contents": "τ̇` 	},
		{ "trigger": "upsilondot`	"contents": "υ̇` 	},
		{ "trigger": "phidot`		"contents": "ϕ̇` 	},
		{ "trigger": "chidot`		"contents": "χ̇` 	},
		{ "trigger": "psidot`		"contents": "ψ̇` 	},
		{ "trigger": "omegadot`	"contents": "ω̇` 	},

// Dot Derivatives - Uppercase Greek letters
		{ "trigger": "Alphadot`	"contents": "Α̇` 	},
		{ "trigger": "Betadot`		"contents": "Β̇` 	},
		{ "trigger": "Gammadot`	"contents": "Γ̇` 	},
		{ "trigger": "Deltadot`	"contents": "Δ̇` 	},
		{ "trigger": "Epsilondot`	"contents": "Ε̇` 	},
		{ "trigger": "Zetadot`		"contents": "Ζ̇` 	},
		{ "trigger": "Etadot`		"contents": "Η̇` 	},
		{ "trigger": "Thetadot`	"contents": "Θ̇` 	},
		{ "trigger": "Iotadot`		"contents": "Ι̇` 	},
		{ "trigger": "Kappadot`	"contents": "Κ̇` 	},
		{ "trigger": "Lambdadot`	"contents": "Λ̇` 	},
		{ "trigger": "Lamdadot`	"contents": "Λ̇` 	},
		{ "trigger": "Mudot`		"contents": "Μ̇` 	},
		{ "trigger": "Nudot`		"contents": "Ν̇` 	},
		{ "trigger": "Xidot`		"contents": "Ξ̇` 	},
		{ "trigger": "Omicrondot`	"contents": "Ο̇` 	},
		{ "trigger": "Pidot`		"contents": "Π̇` 	},
		{ "trigger": "Rhodot`		"contents": "Ρ̇` 	},
		{ "trigger": "Sigmadot`	"contents": "Σ̇` 	},
		{ "trigger": "Taudot`		"contents": "Τ̇` 	},
		{ "trigger": "Upsilondot`	"contents": "Υ̇` 	},
		{ "trigger": "Phidot`		"contents": "Φ̇` 	},
		{ "trigger": "Chidot`		"contents": "Χ̇` 	},
		{ "trigger": "Psidot`		"contents": "Ψ̇` 	},
		{ "trigger": "Omegadot`	"contents": "Ω̇` 	},

// Double-Dot Derivatives - Lowercase Roman letters
		{ "trigger": "addot`		"contents": "ä` 	},
		{ "trigger": "bddot`		"contents": "b̈` 	},
		{ "trigger": "cddot`		"contents": "c̈` 	},
		{ "trigger": "dddot`		"contents": "d̈` 	},
		{ "trigger": "eddot`		"contents": "ë` 	},
		{ "trigger": "fddot`		"contents": "f̈` 	},
		{ "trigger": "gddot`		"contents": "g̈` 	},
		{ "trigger": "hddot`		"contents": "ḧ` 	},
		{ "trigger": "iddot`		"contents": "ï` 	},
		{ "trigger": "jddot`		"contents": "j̈` 	},
		{ "trigger": "kddot`		"contents": "k̈` 	},
		{ "trigger": "lddot`		"contents": "l̈` 	},
		{ "trigger": "mddot`		"contents": "m̈` 	},
		{ "trigger": "nddot`		"contents": "n̈` 	},
		{ "trigger": "oddot`		"contents": "ö` 	},
		{ "trigger": "pddot`		"contents": "p̈` 	},
		{ "trigger": "qddot`		"contents": "q̈` 	},
		{ "trigger": "rddot`		"contents": "r̈` 	},
		{ "trigger": "sddot`		"contents": "s̈` 	},
		{ "trigger": "tddot`		"contents": "ẗ` 	},
		{ "trigger": "uddot`		"contents": "ü` 	},
		{ "trigger": "vddot`		"contents": "v̈` 	},
		{ "trigger": "wddot`		"contents": "ẅ` 	},
		{ "trigger": "xddot`		"contents": "ẍ` 	},
		{ "trigger": "yddot`		"contents": "ÿ` 	},
		{ "trigger": "zddot`		"contents": "z̈` 	},

// ddot Derivatives - Uppercase Roman letters
		{ "trigger": "Addot`		"contents": "Ä` 	},
		{ "trigger": "Bddot`		"contents": "B̈` 	},
		{ "trigger": "Cddot`		"contents": "C̈` 	},
		{ "trigger": "Dddot`		"contents": "D̈` 	},
		{ "trigger": "Eddot`		"contents": "Ë` 	},
		{ "trigger": "Fddot`		"contents": "F̈` 	},
		{ "trigger": "Gddot`		"contents": "G̈` 	},
		{ "trigger": "Hddot`		"contents": "Ḧ` 	},
		{ "trigger": "Iddot`		"contents": "Ï` 	},
		{ "trigger": "Jddot`		"contents": "J̈` 	},
		{ "trigger": "Kddot`		"contents": "K̈` 	},
		{ "trigger": "Lddot`		"contents": "L̈` 	},
		{ "trigger": "Mddot`		"contents": "M̈` 	},
		{ "trigger": "Nddot`		"contents": "N̈` 	},
		{ "trigger": "Oddot`		"contents": "Ö` 	},
		{ "trigger": "Pddot`		"contents": "P̈` 	},
		{ "trigger": "Qddot`		"contents": "Q̈` 	},
		{ "trigger": "Rddot`		"contents": "R̈` 	},
		{ "trigger": "Sddot`		"contents": "S̈` 	},
		{ "trigger": "Tddot`		"contents": "T̈` 	},
		{ "trigger": "Uddot`		"contents": "Ü` 	},
		{ "trigger": "Vddot`		"contents": "V̈` 	},
		{ "trigger": "Wddot`		"contents": "Ẅ` 	},
		{ "trigger": "Xddot`		"contents": "Ẍ` 	},
		{ "trigger": "Yddot`		"contents": "Ÿ` 	},
		{ "trigger": "Zddot`		"contents": "Z̈` 	},

// Double-dot Derivatives - Lowercase Greek letters
		{ "trigger": "alphaddot`	"contents": "α̈` 	},
		{ "trigger": "betaddot`	"contents": "β̈` 	},
		{ "trigger": "gammaddot`	"contents": "γ̈` 	},
		{ "trigger": "deltaddot`	"contents": "δ̈` 	},
		{ "trigger": "epsilonddot`	"contents": "ε̈` 	},
		{ "trigger": "zetaddot`	"contents": "ζ̈` 	},
		{ "trigger": "etaddot`		"contents": "η̈` 	},
		{ "trigger": "thetaddot`	"contents": "θ̈` 	},
		{ "trigger": "iotaddot`	"contents": "ϊ` 	},
		{ "trigger": "kappaddot`	"contents": "κ̈` 	},
		{ "trigger": "lambdaddot`	"contents": "λ̈` 	},
		{ "trigger": "lamdaddot`	"contents": "λ̈` 	},
		{ "trigger": "muddot`		"contents": "μ̈` 	},
		{ "trigger": "nuddot`		"contents": "ν̈` 	},
		{ "trigger": "xiddot`		"contents": "ξ̈` 	},
		{ "trigger": "omicronddot`	"contents": "ο̈` 	},
		{ "trigger": "piddot`		"contents": "π̈` 	},
		{ "trigger": "rhoddot`		"contents": "ρ̈` 	},
		{ "trigger": "sigmaddot`	"contents": "σ̈` 	},
		{ "trigger": "tauddot`		"contents": "τ̈` 	},
		{ "trigger": "upsilonddot`	"contents": "ϋ` 	},
		{ "trigger": "phiddot`		"contents": "ϕ̈` 	},
		{ "trigger": "chiddot`		"contents": "χ̈` 	},
		{ "trigger": "psiddot`		"contents": "ψ̈` 	},
		{ "trigger": "omegaddot`	"contents": "ω̈` 	},

// Double-dot Derivatives - Uppercase Greek letters
		{ "trigger": "Alphaddot`	"contents": "Α̈` 	},
		{ "trigger": "Betaddot`	"contents": "Β̈` 	},
		{ "trigger": "Gammaddot`	"contents": "Γ̈` 	},
		{ "trigger": "Deltaddot`	"contents": "Δ̈` 	},
		{ "trigger": "Epsilonddot`	"contents": "Ε̈` 	},
		{ "trigger": "Zetaddot`	"contents": "Ζ̈` 	},
		{ "trigger": "Etaddot`		"contents": "Η̈` 	},
		{ "trigger": "Thetaddot`	"contents": "Θ̈` 	},
		{ "trigger": "Iotaddot`	"contents": "Ϊ` 	},
		{ "trigger": "Kappaddot`	"contents": "Κ̈` 	},
		{ "trigger": "Lambdaddot`	"contents": "Λ̈` 	},
		{ "trigger": "Lamdaddot`	"contents": "Λ̈` 	},
		{ "trigger": "Muddot`		"contents": "Μ̈` 	},
		{ "trigger": "Nuddot`		"contents": "Ν̈` 	},
		{ "trigger": "Xiddot`		"contents": "Ξ̈` 	},
		{ "trigger": "Omicronddot`	"contents": "Ο̈` 	},
		{ "trigger": "Piddot`		"contents": "Π̈` 	},
		{ "trigger": "Rhoddot`		"contents": "Ρ̈` 	},
		{ "trigger": "Sigmaddot`	"contents": "Σ̈` 	},
		{ "trigger": "Tauddot`		"contents": "Τ̈` 	},
		{ "trigger": "Upsilonddot`	"contents": "Ϋ` 	},
		{ "trigger": "Phiddot`		"contents": "Φ̈` 	},
		{ "trigger": "Chiddot`		"contents": "Χ̈` 	},
		{ "trigger": "Psiddot`		"contents": "Ψ̈` 	},
		{ "trigger": "Omegaddot`	"contents": "Ω̈` 	},



// Superscripts - Roman numerals
		{ "trigger": "^0` 			"contents": "⁰"		},
		{ "trigger": "^1` 			"contents": "¹"		},
		{ "trigger": "^2` 			"contents": "²"		},
		{ "trigger": "^3` 			"contents": "³"		},
		{ "trigger": "^4` 			"contents": "⁴"		},
		{ "trigger": "^5` 			"contents": "⁵"		},
		{ "trigger": "^6` 			"contents": "⁶"		},
		{ "trigger": "^7` 			"contents": "⁷"		},
		{ "trigger": "^8` 			"contents": "⁸"		},
		{ "trigger": "^9` 			"contents": "⁹"		},

// Superscripts - Uppercase Roman Letters
		{ "trigger": "^A` 			"contents": "ᴬ"		},
		{ "trigger": "^B` 			"contents": "ᴮ"		},
		{ "trigger": "^D` 			"contents": "ᴰ"		},
		{ "trigger": "^E` 			"contents": "ᴱ"		},
		{ "trigger": "^G` 			"contents": "ᴳ"		},
		{ "trigger": "^H` 			"contents": "ᴴ"		},
		{ "trigger": "^I` 			"contents": "ᴵ"		},
		{ "trigger": "^J` 			"contents": "ᴶ"		},
		{ "trigger": "^K` 			"contents": "ᴷ"		},
		{ "trigger": "^L` 			"contents": "ᴸ"		},
		{ "trigger": "^M` 			"contents": "ᴹ"		},
		{ "trigger": "^N` 			"contents": "ᴺ"		},
		{ "trigger": "^O` 			"contents": "ᴼ"		},
		{ "trigger": "^P` 			"contents": "ᴾ"		},
		{ "trigger": "^R` 			"contents": "ᴿ"		},
		{ "trigger": "^T` 			"contents": "ᵀ"		},
		{ "trigger": "^U` 			"contents": "ᵁ"		},
		{ "trigger": "^V` 			"contents": "ⱽ"		},
		{ "trigger": "^W` 			"contents": "ᵂ"		},

// Superscripts - Lowercase Roman Letters
		{ "trigger": "^a` 			"contents": "ᵃ"		},
		{ "trigger": "^b` 			"contents": "ᵇ"		},
		{ "trigger": "^c` 			"contents": "ᶜ"		},
		{ "trigger": "^d` 			"contents": "ᵈ"		},
		{ "trigger": "^e` 			"contents": "ᵉ"		},
		{ "trigger": "^f` 			"contents": "ᶠ"		},
		{ "trigger": "^g` 			"contents": "ᵍ"		},
		{ "trigger": "^h` 			"contents": "ʰ"		},
		{ "trigger": "^i` 			"contents": "ⁱ"		},
		{ "trigger": "^j` 			"contents": "ʲ"		},
		{ "trigger": "^k` 			"contents": "ᵏ"		},
		{ "trigger": "^l` 			"contents": "ˡ"		},
		{ "trigger": "^m` 			"contents": "ᵐ"		},
		{ "trigger": "^n` 			"contents": "ⁿ"		},
		{ "trigger": "^o` 			"contents": "ᵒ"		},
		{ "trigger": "^p` 			"contents": "ᵖ"		},
		{ "trigger": "^r` 			"contents": "ʳ"		},
		{ "trigger": "^s` 			"contents": "ˢ"		},
		{ "trigger": "^t` 			"contents": "ᵗ"		},
		{ "trigger": "^u` 			"contents": "ᵘ"		},
		{ "trigger": "^v` 			"contents": "ᵛ"		},
		{ "trigger": "^w` 			"contents": "ʷ"		},
		{ "trigger": "^x` 			"contents": "ˣ"		},
		{ "trigger": "^y` 			"contents": "ʸ"		},
		{ "trigger": "^z` 			"contents": "ᶻ"		},

// Superscripts - Lowercase Greek letters
		{ "trigger": "^β` 			"contents": "ᵝ"		},
		{ "trigger": "^γ` 			"contents": "ᵞ"		},
		{ "trigger": "^δ` 			"contents": "ᵟ"		},
		{ "trigger": "^θ` 			"contents": "ᶿ"		},
		{ "trigger": "^ι` 			"contents": "ᶥ"		},
		{ "trigger": "^ϕ` 			"contents": "ᵠ"		},
		{ "trigger": "^χ` 			"contents": "ᵡ"		},

// Subscripts - Roman Numerals
		{ "trigger": "_0` 			"contents": "₀"		},
		{ "trigger": "_1` 			"contents": "₁"		},
		{ "trigger": "_2` 			"contents": "₂"		},
		{ "trigger": "_3` 			"contents": "₃"		},
		{ "trigger": "_4` 			"contents": "₄"		},
		{ "trigger": "_5` 			"contents": "₅"		},
		{ "trigger": "_6` 			"contents": "₆"		},
		{ "trigger": "_7` 			"contents": "₇"		},
		{ "trigger": "_8` 			"contents": "₈"		},
		{ "trigger": "_9` 			"contents": "₉"		},

// Subscripts - Lowercase Roman letters
		{ "trigger": "_a` 			"contents": "ₐ"		},
		{ "trigger": "_e` 			"contents": "ₑ"		},
		{ "trigger": "_i` 			"contents": "ᵢ"		},
		{ "trigger": "_j` 			"contents": "ⱼ"		},
		{ "trigger": "_o` 			"contents": "ₒ"		},
		{ "trigger": "_r` 			"contents": "ᵣ"		},
		{ "trigger": "_u` 			"contents": "ᵤ"		},
		{ "trigger": "_v` 			"contents": "ᵥ"		},
		{ "trigger": "_x` 			"contents": "ₓ"		},

// Subscripts - lowercase Greek letters
		{ "trigger": "_beta` 		"contents": "ᵦ"		},
		{ "trigger": "_gamma` 		"contents": "ᵧ"		},
		{ "trigger": "_rho` 		"contents": "ᵨ"		},
		{ "trigger": "_phi` 		"contents": "ᵩ"		},
		{ "trigger": "_chi` 		"contents": "ᵪ"		},





		{ "trigger": "rsun` 		"contents": "R☉" 	},
		{ "trigger": "reSun` 		"contents": "R☉" 	},
		{ "trigger": "msun` 		"contents": "m☉" 	},
		{ "trigger": "musun` 		"contents": "μ☉" 	},
		{ "trigger": "alphasun`	"contents": "α☉" 	},
		{ "trigger": "deltasun`	"contents": "δ☉" 	},

		{ "trigger": "rearth` 		"contents": "R⨁" 	},
		{ "trigger": "reEarth` 	"contents": "R⨁" 	},
		{ "trigger": "mearth` 		"contents": "m⨁" 	},
		{ "trigger": "muearth` 	"contents": "μ⨁" 	},
		{ "trigger": "omegaearth` 	"contents": "ω⨁" 	},

		{ "trigger": "rmoon` 		"contents": "R☾" 	},
		{ "trigger": "reMoon` 		"contents": "R☾" 	},
		{ "trigger": "mumoon` 		"contents": "μ☾" 	},
		{ "trigger": "alphamoon` 	"contents": "α☾" 	},
		{ "trigger": "deltamoon` 	"contents": "δ☾" 	},

// Celestial bodies
		{ "trigger": "sun` 		"contents": "☉" 	},
		{ "trigger": "mercury` 	"contents": "☿" 	},
		{ "trigger": "venus` 		"contents": "♀" 	},
		{ "trigger": "earth` 		"contents": "⨁"		},
		{ "trigger": "moon` 		"contents": "☾" 	},
		{ "trigger": "mars` 		"contents": "♂" 	},
		{ "trigger": "jupiter` 	"contents": "♃" 	},
		{ "trigger": "saturn` 		"contents": "♄" 	},
		{ "trigger": "uranus` 		"contents": "♅" 	},
		{ "trigger": "neptune` 	"contents": "♆" 	},
		{ "trigger": "pluto` 		"contents": "♇" 	},


		{ "trigger": "epsilonbar` 	"contents": "ε̄" 	},
		{ "trigger": "omegatilde` 	"contents": "ω̃" 	},


		{ "trigger": "2pi`			"contents": "2π" 	},
		{ "trigger": "micro`		"contents": "μ" 	},
		{ "trigger": "check`		"contents": "✓" 	},

		{ "trigger": "lat`			"contents": "ϕ" 	},
		{ "trigger": "lon`			"contents": "λ" 	},

		{ "trigger": "dot`			"contents": "̇" 		},
		{ "trigger": "ddot`		"contents": "̈" 		},
		{ "trigger": "vec`			"contents": "⃗" 		},
		{ "trigger": "bar`			"contents": "̄" 		},
		{ "trigger": "tilde`		"contents": "̃" 		},



		{ "trigger": "deg` 		"contents": "°" 	},
		{ "trigger": "degree` 		"contents": "°" 	},
		{ "trigger": "pm` 			"contents": "±" 	},
		{ "trigger": "neq` 		"contents": "≠" 	},
		{ "trigger": "cross` 		"contents": "⨯" 		},
		{ "trigger": "mult` 		"contents": "⨯" 		},
		{ "trigger": "div` 		"contents": "÷" 	},
		{ "trigger": "cbrt` 		"contents": "∛" 	},
		{ "trigger": "sqrt` 		"contents": "√" 	},
		{ "trigger": "prime` 		"contents": "′" 	},
		{ "trigger": "pprime` 		"contents": "″" 	},
		{ "trigger": "ppprime` 	"contents": "‴" 	},
		{ "trigger": "pppprime` 	"contents": "⁗" 	},
		{ "trigger": "leftarrow` 	"contents": "←" 	},
		{ "trigger": "rightarrow` 	"contents": "→" 	},
		{ "trigger": "leftrightarrow`"contents": "↔" 	},
		{ "trigger": "uparrow` 	"contents": "↑" 	},
		{ "trigger": "downarrow` 	"contents": "↓" 	},
		{ "trigger": "updownarrow` "contents": "↕" 	},

		{ "trigger": "larr` 		"contents": "←" 	},
		{ "trigger": "rarr` 		"contents": "→" 	},
		{ "trigger": "lrarr`		"contents": "↔" 	},
		{ "trigger": "uarr` 		"contents": "↑" 	},
		{ "trigger": "darr` 		"contents": "↓" 	},
		{ "trigger": "udarr` 		"contents": "↕" 	}