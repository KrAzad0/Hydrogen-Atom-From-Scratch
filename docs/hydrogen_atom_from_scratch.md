# Hydrogen Atom From Scratch

## 1. Physical system

The hydrogen atom consists of one electron and one proton interacting through the Coulomb force. In nonrelativistic quantum mechanics this is a two-body problem.

Classically, the Hamiltonian is the sum of the kinetic energies of the electron and proton plus the attractive Coulomb potential.

## 2. Reduction to one-body form

Introduce center-of-mass and relative coordinates. This separates the motion into:

- free center-of-mass motion
- relative motion in a central Coulomb potential

The key quantity is the reduced mass:

mu = (m_e m_p) / (m_e + m_p)

The relative Hamiltonian is then:

H_rel = p^2 / (2 mu) - e^2 / (4 pi epsilon_0 r)

## 3. Schrödinger equation

Quantizing momentum gives the time-independent equation:

[-hbar^2 / (2 mu) nabla^2 - e^2 / (4 pi epsilon_0 r)] psi(r) = E psi(r)

Because the potential depends only on the distance r, this is a central-force problem.

## 4. Spherical coordinates

The wavefunction is separated as:

psi(r, theta, phi) = R(r) Y(theta, phi)

The angular part is described by spherical harmonics and the quantum numbers l and m.

## 5. Radial equation

The radial function satisfies the standard hydrogen radial equation. Imposing finiteness at the origin and normalizability at infinity leads to discrete bound-state energies.

## 6. Bohr radius and spectrum

The characteristic length scale is the Bohr radius:

a_0 = 4 pi epsilon_0 hbar^2 / (mu e^2)

The bound-state energies are:

E_n = - mu e^4 / [2 (4 pi epsilon_0)^2 hbar^2] times 1/n^2

For hydrogen this is approximately:

E_n = -13.6 eV / n^2

## 7. Quantum numbers

The stationary states are labeled by:

- n: principal quantum number
- l: orbital angular momentum quantum number
- m: magnetic quantum number

The allowed values are:

- n = 1, 2, 3, ...
- l = 0, 1, ..., n-1
- m = -l, ..., +l

## 8. Ground state

The ground state corresponds to:

- n = 1
- l = 0
- m = 0

Its wavefunction is proportional to exp(-r/a_0), and the most probable radius is the Bohr radius.

## 9. Spectral lines

Transitions between discrete levels produce hydrogen spectral lines. The photon energy is the difference between two energy levels.

This leads to the Rydberg formula and the familiar Lyman, Balmer, and Paschen series.

## 10. Selection rules

For electric dipole transitions, the main selection rules are:

- Delta l = plus or minus 1
- Delta m = 0, plus or minus 1

## 11. Beyond the basic model

A more complete treatment of hydrogen includes:

- electron spin
- fine structure
- spin-orbit coupling
- Lamb shift
- hyperfine structure

## 12. Summary

The hydrogen atom is the exact solvable nonrelativistic problem of a particle with reduced mass moving in an attractive 1/r potential. It is the foundational model of atomic quantum mechanics.
