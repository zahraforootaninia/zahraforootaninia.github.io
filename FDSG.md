

## Frequency-Domain Smoke Guiding

Zahra Forootaninia
University of Minnesota
Rahul Narain
Indian Institute of Technology Delhi


SIGGRAPH Asia 2020

Abstract: We propose a simple and efficient method for guiding an Eulerian smoke simulation to match the behavior of a specified velocity field, such as a low-resolution animation of the same scene, while preserving the rich, turbulent details arising in the simulated fluid. Our method works by simply combining the high-frequency component of the simulated fluid velocity with the low-frequency component of the input guiding field. In contrast to previous work, we show that it is essential to use ideal low-pass and high-pass filters in the frequency domain, in order to avoid artifacts resulting from loss of small-scale details over time.We demonstrate our method on many scenes including those with static and moving obstacles, and show that it produces high-quality results with very little computational overhead.


[Paper (14.2 MB)](./pdfs/FD_smoke_guiding.pdf)
[Code [Bitbucket]](./https://bitbucket.org/zahrafn/frequency_domain_smoke_guiding/src/master/)

[back](./)
