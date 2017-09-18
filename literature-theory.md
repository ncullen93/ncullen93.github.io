---
title: ANTs | Literature Theory
id: literature-theory
permalink: /literature-theory/
layout: research
---
< <a href="/literature/">Back to Literature</a>

# ANTs methodology in the scientific literature

The theory and methodology behind ANTs-based tools have been described in numerous papers. 
In this section, we discuss various papers that go in-depth about the theory 
and methodology behind ANTs. If you want to read literature about ANTs or are 
looking for papers to cite after using ANTs-based tools, then this the section is for you.

----------------------------------------------------------------

## <b>Image Registration</b>
<br />
Image registration refers to the alignment of two or more images into a common space. This is
the bread-and-butter of ANTs.

### <i>Diffeomorphic Registration</i>

Diffeomorphic registration is a type of registration which produces invertible maps describing
a local deformation field at each voxel. This method is validated against gold standard data,
and is known to perform particularly well when the distance between the template brain and the
target brain is large.

- Avants BB, Epstein CL, Grossman M, Gee JC. "Symmetric Diffeomorphic Image Registration with 
Cross-Correlation: Evaluating Automated Labeling of Elderly and Neurodegenerative Brain." Medical image analysis. 2008;12(1):26-41. 
doi:10.1016/j.media.2007.06.004. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/17659998))

### <i>Independent Evaluation of ANTs Registration</i>

How can we be sure that ANTs registration tools are effective? And how do they compare against 
other commonly used registration tools? This is where independent evaluations come into play. The 
ANTs core team has published numerous studies evaluating our methods on gold standard data.

- Klein A, Andersson J, Ardekani BA, et al. Evaluation of 14 nonlinear deformation algorithms 
applied to human brain MRI registration. NeuroImage. 2009;46(3):786-802. 
doi:10.1016/j.neuroimage.2008.12.037. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/19195496))

- K. Murphy, B. van Ginneken, ..., “Evaluation of registration
methods on thoracic CT: The empire10 challenge,” IEEE Trans. Med. 
Imag., vol. 30, no. 11, pp. 1901–1920, Nov. 2011. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/21632295))

- Avants BB, Tustison NJ, Song G, Cook PA, Klein A, Gee JC. A Reproducible Evaluation of 
ANTs Similarity Metric Performance in Brain Image Registration. NeuroImage.
2011;54(3):2033-2044. doi:10.1016/j.neuroimage.2010.09.025. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/20851191))


### <i>Template Construction</i>

Constructing templates is central to the normalization process. Templates allow you to 
encode population-level prior information and provide a common space for normalizing images.

- Brian Avants, James C. Gee, Geodesic estimation for large deformation anatomical shape averaging and 
interpolation, In NeuroImage, Volume 23, Supplement 1, 2004, Pages S139-S150, 
ISSN 1053-8119, https://doi.org/10.1016/j.neuroimage.2004.07.010. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/15501083))

- Avants BB, Yushkevich P, Pluta J, et al. The Optimal Template Effect in Hippocampus Studies of 
Diseased Populations. NeuroImage. 2010;49(3):2457. doi:10.1016/j.neuroimage.2009.09.062. 
([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/19818860))

----------------------------------------------------------------
## <b>Image Segmentation</b>
<br />
Image segmentation refers to the problem of assigning one of multiple discrete classes to every location 
in an image. Typical segmentation tasks include skull stripping, segmenting the brain into gray matter and
white matter, or atlas-based methods to achieve entire parcellations. ANTs-based tools achieve strong results 
on all of the major segmentation tasks, and continues to push the state-of-the-art.

### <i>Tissue segmentation</i>


Our <i>Atropos</i> algorithm is a go-to method for n-class tissue segmentation. This algorithm uses 
multivariate expectation maximization of Markov random fields to incorporate prior knowledge
that achieves strong results even with non-standard images.

- Avants BB, Tustison NJ, Wu J, Cook PA, Gee JC. An Open Source Multivariate Framework 
for n-Tissue Segmentation with Evaluation on Public Data. Neuroinformatics. 
2011;9(4):381-400. doi:10.1007/s12021-011-9109-y. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/21373993))

<img style="height:500px;" src="/static/img/ants-figures/atropos-figure.png">


### <i>Multi-atlas segmentation</i>

Our multi-atlas segmentation method is a meta-algorithm which greatly improves performane, albeit
with increased computation time. This method performs particularly well in typically difficult 
tasks such as hippocampus segmentation.

- Wang H, Das SR, Suh JW, et al. A Learning-Based Wrapper Method to Correct 
Systematic Errors in Automatic Image Segmentation: Consistently Improved 
Performance in Hippocampus, Cortex and Brain Segmentation. NeuroImage. 
2011;55(3):968-985. doi:10.1016/j.neuroimage.2011.01.006. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/21237273))


### <i>DiReCT cortical thickness estimation</i>

The DiReCT algorithm is a registration-based method for estimating cortical thickness in the 
brain. The greater ANTs cortical thickness pipeline is a well-validated method commonly used
in the literature for investigating imaging biomarkers.

- Das SR, Avants BB, Grossman M, Gee JC. Registration Based Cortical Thickness 
Measurement. NeuroImage. 2009;45(3):867-879. doi:10.1016/j.neuroimage.2008.12.016.
([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/19150502))

- Nicholas J. Tustison, Philip A. Cook, Arno Klein, Gang Song, Sandhitsu R. Das, 
Jeffrey T. Duda, Benjamin M. Kandel, Niels van Strien, James R. Stone,
James C. Gee, Brian B. Avants, Large-scale evaluation of ANTs and 
FreeSurfer cortical thickness measurements, In NeuroImage, Volume 99, 2014, 
Pages 166-179, ISSN 1053-8119, https://doi.org/10.1016/j.neuroimage.2014.05.044.
([link to paper](https://www.ncbi.nlm.nih.gov/pubmed/24879923))

The DiReCT method has also been validated in chimpanzees:

- Hopkins WD, Avants BB. Regional and Hemispheric Variation in Cortical Thickness 
in Chimpanzees (Pan troglodytes). The Journal of neuroscience : 
the official journal of the Society for Neuroscience. 2013;33(12):5241-5248. 
doi:10.1523/JNEUROSCI.2996-12.2013. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/23516289))

----------------------------------------------------------------
## <b>Multivariate Statistical Analysis</b>
<br />
ANTs is also a useful tool to carry out multivariate statistical analysis on imaging and behavioral 
features. Using ANTs as an end-to-end processing and analysis reduces systematic error and improves
generalizability of results. The analysis capabilities of the ANTsX ecosystem are broad and 
well-validated in the literature.

### <i>Eigenanatomy</i>
Particularly, our <i>Eigenanatomy</i> tools provide a suite of analysis methods capable of 
investigating sparse, multi-modal relationships between imaging and behavioral data.

- Avants B, Dhillon P, Kandel BM, et al. Eigenanatomy improves detection power 
for longitudinal cortical change. Medical image computing and 
computer-assisted intervention : MICCAI . International Conference 
on Medical Image Computing and Computer-Assisted Intervention. 
2012;15(0 3):206-213. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/23286132))

Additionally, we have implementations of <i>Sparse CCA</i> and <i>Sparse Regression</i> 
which provide biologically-plausible results and high performance in the context of brain images.

- Avants BB, Cook PA, Ungar L, Gee JC, Grossman M. Dementia Induces Correlated 
Reductions in White Matter Integrity and Cortical Thickness: A Multivariate 
Neuroimaging Study with Sparse Canonical Correlation Analysis. NeuroImage. 
2010;50(3):1004-1016. doi:10.1016/j.neuroimage.2010.01.041. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/20083207))

- Avants B, Cook PA, McMillan C, et al. Sparse Unbiased Analysis of Anatomical Variance 
in Longitudinal Imaging. Medical image computing and computer-assisted intervention : 
MICCAI . International Conference on Medical Image Computing and Computer-Assisted 
Intervention. 2010;13(0 1):324-331. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/20879247))


- Kandel, Benjamin M. and Wolk, David A. and Gee, James C. and Avants, Brian. 
Predicting Cognitive Data from Medical Images Using Sparse Linear Regression. 
Springer Berlin Heidelberg, 2013 ([link to paper](http://link.springer.com/chapter/10.1007%2F978-3-642-38868-2_8))


Also, multivariate analysis of registration results can be useful:

- Brian Avants, Jeffrey T. Duda, Junghoon Kim, Hui Zhang, John Pluta, James C. Gee, 
John Whyte, Multivariate Analysis of Structural and Diffusion Imaging in 
Traumatic Brain Injury, In Academic Radiology, Volume 15, Issue 11, 2008, 
Pages 1360-1375, ISSN 1076-6332, https://doi.org/10.1016/j.acra.2008.07.007.
([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/18995188))


### Other

N4 Bias Correction:

- Tustison NJ, Avants BB, Cook PA, et al. N4ITK: Improved N3 Bias 
Correction. IEEE transactions on medical imaging. 2010;29(6):1310-1320. 
doi:10.1109/TMI.2010.2046908. ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/20378467))

Statistical bias:

- Tustison, N. J., Avants, B. B., Cook, P. A., Kim, J., Whyte, J., 
Gee, J. C. and Stone, J. R. (2014), Logical circularity in voxel-based 
analysis: Normalization strategy may induce statistical bias. Hum.
 Brain Mapp, 35: 745–759. doi:10.1002/hbm.22211 ([link to paper](http://www.ncbi.nlm.nih.gov/pubmed/23151955))




