In this paper, we aim to jointly model the geometry,
appearance, and physical information of 3D scenes solely from
dynamic multi-view videos, without relying on any physical
priors. Existing works typically employ physical losses merely
as soft constraints or integrate physical simulations into neural
networks; however, these approaches often fail to effectively
learn complex motion physics. Although modeling velocity fields
holds the potential to capture authentic physical information,
due to the lack of appropriate physical constraints, current
methods are unable to correctly learn the interaction mechanisms
between rigid and non-rigid particles. To address this, we propose
VeloGauss, designed to learn the physical properties of complex
dynamic 3D scenes without physical priors. Our method learns
the velocity field for each Gaussian particle by introducing a
Physics Code and a Particle Dynamics System, and ultimately
incorporates Global Physical Constraints to ensure the physical
consistency of the scene. Extensive experiments on four public
datasets demonstrate that our method achieves state-of-the-art
performance in both Novel View Interpolation and Future Frame
Extrapolation tasks.
