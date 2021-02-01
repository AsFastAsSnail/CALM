# CALM
ConservAtion Laws Model

Authors: M. A. Janik, A. Zaborowska, P. Modzelewski, F. Skóra, D. M. Rodak

Latest version: 1.1

Helpers
------------------------------
   * CALM-manual.pdf - manual with more specific description of how CALM works.

Quick start manual
------------------------------
Depedencies:

   * C++ compiler
   * Cmake
   * ROOT (http://root.cern.ch/)

Installation:

      mkdir build
      cd build
      cmake ..
      make
   
   
   If cmake fails to find ROOT package, you can specify its path via:
   
      cmake -DROOTSYS='your_path_to_root_installation_e_g_/opt/root' ..
      
Capabilities
------------------------------
CALM simulates proton-proton collisions and saves their results into files. It produces 13 types of hadrons, we can distinguish them into 4 kinds:
   1. Pions (π<sup>+</sup>, π<sup>0</sup>, π<sup>-</sup>)
   2. Kaons (K<sup>+</sup>, K<sup>0</sup>, anti-K<sup>0</sup> , K<sup>-</sup>)
   3. Nukleons (p, anti-p, n, anti-n)
   4. Lambdas (Λ, anti-Λ)
You can analyze CALM results by your own or by using [tpi program](https://github.com/majanik/tpi_CALM).
