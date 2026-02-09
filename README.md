A small project that demonstrates a Python simulation that integrates a relativistic charged particle in a uniform magnetic field using
a Boris-style push, with a simple Monte Carlo model for interactions:
 - Mean free path for interactions (exponential distribution)
 - At each interaction the particle loses a fixed fraction of kinetic energy and is
   scattered by a small random angle (added as a separate file)
 - Deposited energy is recorded and binned vs depth (z)
 - Normalized units: c = 1, m = 1, q = +-1.
