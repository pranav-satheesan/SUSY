The data consists of Monte Carlo simulations of both supersymmetric and non-supersymmetric collision events. This is simulating the collision two leptons, either muons or electrons, under the assumption of baseline Standard Model physics or the assumption of supersymmetric physics. In particle physics, Monte Carlo simulations are often used to model the behavior of particles in high-energy collisions, such as those that occur in large particle accelerators like the Large Hadron Collider (LHC). These simulations involve a random sampling process to approximate the outcome of complex phenomena. These simulations are critical to validate theoretical models and to predict what signals a new physics process might create in a detector.

Supersymmetry (SUSY) is a theoretical framework in particle physics that proposes a symmetry principle connecting fermions (particles with half-integer spin) and bosons (particles with integer spin). This innovative theory introduces the concept of a supersymmetric partner for each known elementary particle, which differs in spin by 1/2 but shares other fundamental properties such as charge and mass.

More details about the dataset used for this project.

The first 8 features are directly measured from the state of the particles after the collision:

lepton 1 pT: momentum transverse to the beamline of lepton 1
lepton 1 eta: pseudo-rapidity of lepton 1
lepton 1 phi: azimuthal angle of lepton 1

lepton 2 pT: momentum transverse to the beamline of lepton 2
lepton 2 eta: pseudo-rapidity of lepton 2
lepton 2 phi: azimuthal angle of lepton 2

missing energy magnitude: the amount of missing transverse momentum
missing energy phi: the azimuthal angle of the missing transverse momentum

The remaining 10 features are derived from the first 8 directly measured features. These last 10 features are features particle physicists have devised to enhance their event detection task. These features are MET_rel, axial MET, M_R, M_TR_2, R, MT2, S_R, M_Delta_R, dPhi_r_b, and cos(theta_r1). 
