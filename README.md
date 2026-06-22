# Lorentzian-Oscillator-Sapphire

Sapphire (α-Al₂O₃) has a strong electronic absorption edge in the UV, a wide transparency window from
the near-UV through the near-IR, and well-separated phonon resonances in the mid- to far-IR. This
makes it an ideal material for relating a microscopic Lorentz-oscillator model to macroscopic dispersion
data.

Task

- Obtain tabulated n(λ) and k(λ) data for sapphire covering the UV through the far-IR.
- Fit the data with a multi-Lorentzian model of the complex susceptibility, χ(ω) = Σᵢ fᵢ ωₚ² / (ωᵢ² −
ω² − 2iγᵢω). Extract the resonance frequencies ωᵢ, damping rates γᵢ, and oscillator strengths fᵢ.
Justify how many oscillators you used and why.
- Use your fitted model to compute the group-velocity dispersion (GVD) at 800 nm. Compare
against the value you obtain by differentiating a published Sellmeier fit of sapphire in the same
transparent region. How much do they agree?
- Check the f-sum rule for your extracted oscillator strengths. In a solid, what should Σᵢ fᵢ
correspond to, and is the rule expected to fail when applied to a fit over a finite spectral range?
- Identify where your fit fails if it does (spectral regions where the Lorentz model cannot
reproduce the data) and discuss possible physical reasons.

My Learning Takeaways

- I now have a good grasp on the classical Lorentz oscillator model for the index of refraction of a material, and I'm starting to understand its strengths and weaknesses. It seems like, in the domain of high-power lasers and nonlinear optics, semi-classical are very commonplace and effective.
- I learned to use nonlinear least squares curve fitting on multi-dimensional and complex-valued functions. This was more difficult than expected, especially figuring out how to use more custom tools for this more tricky application (scipy least-squares instead of curve-fit). This will be useful for the numerous data-driven tasks in my future!
- I had my first experience searching the scientific literature for answers motivated by my results, in the extension tasks. This was quite difficult, but I foudn it fulfilling to start to understand the scientific conversation. 
