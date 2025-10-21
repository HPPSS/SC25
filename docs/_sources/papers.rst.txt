.. _presentations:

Presentations
+++++++++++++

.. |HPPSS| raw:: html

   <a href="https://sc24.conference-program.com/session/?sess=sess761" target="_blank">SC24 HPPSS Schedule</a>

.. |HPPSSZen| raw:: html

   <a href="https://zenodo.org/communities/hppss/records" target="_blank">HPPSS Zenodo Community with Recorded Demos</a>

Here are a few key links for this workshop:

* |HPPSS| 
* |HPPSSZen| 


Demos
=====

.. |Arkouda| raw:: html

   <a href="https://sc24.conference-program.com/presentation/?id=ws_hppss102&sess=sess761" target="_blank">SC Presentation</a>

.. |ArkoudaPaper| raw:: html

   <a href="_static/arkouda-demo-hppss.pdf" target="_blank">Short Paper</a>

.. |ArkoudaZen| raw:: html

   <a href="https://zenodo.org/records/14052268" target="_blank">Demo Recording</a>

.. |CUDA| raw:: html

    <a href="https://sc24.conference-program.com/?post_type=page&p=14&id=ws_hppss104&sess=sess761" target="_blank">SC Presentation</a>

.. |cuNumeric| raw:: html

   <a href="https://sc24.conference-program.com/?post_type=page&p=14&id=ws_hppss106&sess=sess761" target="_blank">SC Presentation</a>

.. |Dragon| raw:: html

   <a href="https://sc24.conference-program.com/?post_type=page&p=14&id=ws_hppss101&sess=sess761" target="_blank">SC Presentation</a>

.. |DragonPaper| raw:: html

   <a href="_static/DragonTelemetryService_SC24_final.pdf" target="_blank">Short Paper</a>

.. |DragonZen| raw:: html

   <a href="https://zenodo.org/records/13327798" target="_blank">Demo Recording</a>

.. |ProxyStore| raw:: html

   <a href="https://sc24.conference-program.com/?post_type=page&p=14&id=ws_hppss103&sess=sess761" target="_blank">SC Presentation</a>

.. |ProxyStorePaper| raw:: html

   <a href="_static/hppss24_dask_proxystore.pdf" target="_blank">Short Paper</a>

.. |ProxyStoreZen| raw:: html

   <a href="https://zenodo.org/records/13328934"  target="_blank">Demo Recording</a>

.. |PyOMP| raw:: html

   <a href="https://sc24.conference-program.com/?post_type=page&p=14&id=ws_hppss105&sess=sess761" target="_blank">SC Presentation</a>

.. |PyOMPZen| raw:: html

   <a href="https://zenodo.org/records/14006515" target="_blank">Demo Recording</a>

.. |PyOMPPaper| raw:: html

   <a href="_static/2024_sc24_hppss_pyomp-final.pdf" target="_blank">Short Paper</a>



Exploring Data Science with Arkouda: A Practical Introduction to Scalable Data Science
--------------------------------------------------------------------------------------

* Presenter: Ben McDonald
* |Arkouda|
* |ArkoudaPaper|
* |ArkoudaZen|



Work-in-progress: CUDA Python object models and parallelism models
------------------------------------------------------------------

* Presenter: Andy Terrel
* |CUDA|



Seamlessly scale your python program from single CPU core to multi-GPU multi-node HPC cluster with cuNumeric
------------------------------------------------------------------------------------------------------------

* Presenter: Wonchan Lee, Manolis Papadakis, Mike Bauer, Bo Dong
* |cuNumeric|



Visualizing Workflows with the Dragon Telemetry Service
-------------------------------------------------------

* Presenter: Indira Pimpalkhare, Colin Wahl, Maria Kalantzi
* |Dragon|
* |DragonPaper|
* |DragonZen|



Accelerating Python Applications with Dask and ProxyStore
---------------------------------------------------------

* Presenter: J. Gregory Pauloski, Klaudiusz Rydzy, Valerie Hayot-Sasson, Ian Foster, Kyle Chard
* |ProxyStore|
* |ProxyStorePaper|
* |ProxyStoreZen|



PyOMP: Parallel programming for CPUs and GPUs with OpenMP and Python
--------------------------------------------------------------------

* Presenter: Giorgis Georgakoudis, Todd Anderson, Stuart Archibald, Bronis de Supinski, Timothy Mattson
* |PyOMP|
* |PyOMPPaper|
* |PyOMPZen|



Lightning Talks
===============

Accelerated massive data analytics for semiconductors
-----------------------------------------------------

Presenter: Quynh L. Nguyen

X-ray experiments at the Linac Coherent Light Source (LCLS), SLAC National Accelerator Laboratory, enables new
scientific discoveries of matter. Accompanied challenges include extracting important insights from massive amount
of data being generated at TeraBytes/hour for effective experiment-steering. This rate will increase to TBs/second with
our newly commissioned LCLS-II/HE facilities. We developed functions in cuNumerics that are relevant for scientific
computing and implemented them for live-analysis during an experiment. We found a 6x speed up as compared to our routine
data analytics using Numpy. By using this new approach, we extract comprehensive information on material properties at
higher efficiency.


In-Transit Machine Learning of Plasma Simulations on Exascale systems
---------------------------------------------------------------------

Presenter: Vineeth Gutta

Traditional ML workflows use offline training where the data is stored on disk and is subsequently loaded into
accelerator (CPU,GPU, etc) memory during training or inference. We recently devised a novel and scalable in-transit
ML workflow for a plasma-physics application (chosen as 1 out of 8 compelling codes in the country) for the world’s
fastest supercomputer, Frontier, with an aim to build a high-energy laser particle accelerator. This in-transit
workflow solves the challenge of coupling full-scale particle-in-cell simulations with distributed ML training on
PyTorch using DDP enabling the model to learn correlations between emitted radiation and particle dynamics within
simulation in an unsupervised method. Simulations on Exascale systems create volumes of data that is infeasible to
store on HPC file systems. A mismatch between modern memory hierarchies occurs due to high volume and rate of data
generation. The workflow demonstrates use of data reduction combined with inversion using invertible neural networks
to reconstruct the simulation. We use continuous learning where the data is consumed in batches as the simulation
produces the data and then discards after each batch is trained. We demonstrate this at scale on Frontier using 400
AMD MI250X GPUs and show the flexibility of such workflows beyond the plasma simulation science case, opening up the
possibility of running in-transit ML with other surrogate models and foundation models.

