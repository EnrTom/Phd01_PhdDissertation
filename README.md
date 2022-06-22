# PhdDissertation

PhD Dissertation By Enrico Tomassoli (enricotomassoli@gmail.com)
PhD Program in “Civil Engineering and Innovative Materials” @ University of Perugia, 2009-2013

Title:
An Energy-based Approach for the Evaluation of the Seismic Response of Structures Using Non-Linear Static Analysis
Original Title (Italian):
Approccio Energetico per la Valutazione della Risposta Sismica delle Strutture Mediante la Analisi Statica Non Lineare

Table of Content:

1 - Main Goal

2 - Project Descriptions

3 - File organization

4 - Source Code used in the Dissertation





1. Main goal

Even if the dissertation is written in Italian, the main goal is to provide an example of how data was created, manipulated, transformed, stored, and used to properly perform the analysis and investigations present in the document.

2. Project Descriptions

Assessment of an energy-based nonlinear static analysis to represent seismic response of structural systems. In this methodology a specific parameter, here called pseudo-energy has been introduced in order to provide a consistent representation of both structural capacity and seismic demand based on an energy criterion. The responses of 2D r/c frames extracted from real tridimensional r/c framed structures and simple 3D systems are considered. In order to assess the reliability of the energy-based method, a comparison with the results of the nonlinear static analysis method suggested by EC8 and the time-history dynamic analysis is performed.
One of the crucial issues in the study is the need for the seismic demand expressed in terms of energy. To overcome this limitation, seismic response spectra in terms of an energetic parameter called pseudo-energy to be used in non-linear static analyses is introduced. Spectra, for different values of ductility, are derived from conventional pseudo-acceleration elastic spectrum using well-known acceleration-displacement-ductility relations reported in literature. Spectra from sets of recorded accelerograms are computed as well, evaluated for EPP and ESH inelastic behaviors. The influence of the main earthquake parameters on the spectra is presented and discussed.
In order to test the robustness and reliability of the proposed methodology, input signals (accelerograms) were necessary. The selection of a set of ground motion accelerograms (recorded, generated or simulated) chosen to reproduce the seismic input in nonlinear dynamics analysis, is typically based on a criterion of compatibility between its average response spectrum and an elastic acceleration, one representative of the site seismic hazard. It can be observed that this approach is not satisfactory for an effective evaluation of the nonlinear seismic response aimed at a performance-based analysis. A different criterion, based on the compatibility of constant ductility spectra is then taken into account for the selection of records. Finally, an energy-based criterion is also proposed, defining an energy parameter, called pseudo-energy, accounting for both the force and displacement in the post-elastic behavior.

3. File organization

In the repository, multiple files are provided. In the following, as brief description of each file and the related use:
PhdDissertation_Enrico Tomassoli: Pdf of dissertation (in Italian) including the Appendix
PhdDissertationPresentation_Enrico Tomassoli: Presentation of the PhD Dissertation in PowerPoint and Pdf format (in English) to summarize the study and the findings of the proposed study.

4. Source Code used in the Dissertation

All the data was created, transformed and stored using Matlab software. All the source codes used for different tasks are saved in specific repositories and additional information is provided for clarity. Please refer to the following repositories for more detail about the scope description and how to run each script:

- EnergyPush
- PlottingSpectra
- AccelerogramSelection
