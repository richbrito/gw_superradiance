# Gravitational waves from boson clouds

This repository contains data and tools that can be used to compute the gravitational wave emission of a scalar cloud around a Kerr black hole. The code was primarily developed in writing [arXiv:1706.06311](https://arxiv.org/abs/1706.06311) and [arXiv:1706.05097](https://arxiv.org/abs/1706.05097) with some improvements since then. In particular,  to obtain the homogenous solutions to the Teukolsky equation when computing the gravitational wave flux, a direct integration method was used in those papers. It is now also possible to use the MST method as implemented in the [Black Hole Perturbation toolkit](http://bhptoolkit.org/Teukolsky/).

Some computations make use of the [Black Hole Perturbation toolkit](http://bhptoolkit.org/Teukolsky/) and also use results from [arXiv:gr-qc/0306120
](https://arxiv.org/abs/gr-qc/0306120), [arXiv:0705.2880](https://arxiv.org/abs/0705.2880) and [arXiv:1312.2326](https://arxiv.org/abs/1312.2326). 

Some of the results for the gravitational-wave flux served as input for the python package [gwaxion](https://pypi.org/project/gwaxion/0.0.1/).

# Credit

Developed and maintained by [Richard Brito](https://richardbrito.weebly.com/). If you make use of the tools or the data for your own publications please cite:

```
@article{Brito:2017zvb,
    author = "Brito, Richard and Ghosh, Shrobana and Barausse, Enrico and Berti, Emanuele and Cardoso, Vitor and Dvorkin, Irina and Klein, Antoine and Pani, Paolo",
    title = "{Gravitational wave searches for ultralight bosons with LIGO and LISA}",
    eprint = "1706.06311",
    archivePrefix = "arXiv",
    primaryClass = "gr-qc",
    doi = "10.1103/PhysRevD.96.064050",
    journal = "Phys. Rev. D",
    volume = "96",
    number = "6",
    pages = "064050",
    year = "2017"
}
