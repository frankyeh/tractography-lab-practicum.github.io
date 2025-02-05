# White Matter Tracts

The white matter tracts of cerebrum can be categorized into three major groups, including commissural pathways, association pathways, and projection pathwas.

Commissural pathways are white matter tracts that connect corresponding regions of the brain across the midline. They are an important component of the brain's structural connectivity, allowing for communication and coordination between the two hemispheres of the brain. The major commissural pathways include the corpus callosum, the anterior commissure, and the posterior commissure.

Association pathways are white matter tracts that connect different areas within the same hemisphere of the brain. They are an important component of the brain's structural connectivity, allowing for communication and coordination between different regions of the brain. Association pathways can be divided into two main types: long association pathways, which connect distant regions of the brain, and short association pathways, which connect adjacent areas.

Projection pathways are white matter tracts that connect the brain cortex to the spinal cord or subcortical regions. They are an important component of the brain's structural connectivity, allowing for communication between the brain cortex and the rest of the nervous system. Projection pathways can be divided into two main types: sensory projection pathways, which transmit sensory information from the body to the brain, and motor projection pathways, which transmit motor commands from the brain to the body.


## Before practicum on Friday, please complete the following:

### White Matter Anatomy 

- Reading: a review on recent known and unknown white matter pathways: [Bullock DN, Hayday EA, Grier MD, Tang W, Pestilli F, Heilbronner S. A taxonomy of the brain’s white matter: Twenty-one major tracts for the twenty-first century.](https://psyarxiv.com/fvk5r/)

- Video: [Computational Neuroanatomy at DIPY Workshop](https://www.youtube.com/watch?v=0gffgCBDOfk)


## During practicum on Friday:

### Review of the assignment 1 (10 min)


### Introduction to white matter pathways (20 min)

<img src="https://ars.els-cdn.com/content/image/1-s2.0-S1053811921009241-gr1_lrg.jpg" width=700>

source: [Neuroimage. 2021 Dec 15;245:118651.](https://www.sciencedirect.com/science/article/pii/S1053811921009241)

- Download and open HCP1065 Group-average template 1mm [[download]](https://zenodo.org/record/6324701/files/HCP1065.1mm.fib.gz?download=1) [(details)](https://brain.labsolver.org/hcp_template.html) in Step T3
- Download and open tractography atlas [[download]](https://pitt-my.sharepoint.com/:f:/g/personal/yehfc_pitt_edu/EjD1HZDMSnVGuuXm_B5vczQBuvY8WFjtHQR-AnXQc6izvQ?e=JIOLDz) [(details)](https://brain.labsolver.org/hcp_trk_atlas.html)
- [simplified atlas](https://github.com/frankyeh/DSI-Studio-atlas/blob/main/ICBM152_adult/ICBM152_adult.tt.gz) and [labels](https://github.com/frankyeh/DSI-Studio-atlas/blob/main/ICBM152_adult/ICBM152_adult.tt.gz.txt)
- [abbreviations](https://pitt-my.sharepoint.com/:x:/g/personal/yehfc_pitt_edu/EQcjg3Ignv5CpOlwRu-dc-sBFy790zDaA2zW0qtR19VbJA?e=gW8L7I)

- White matter pathways can be categorized into commissural, association, and projection pathways.
  - **Commissural pathways**: pathways connecting left and right hemisphere
    - anterior commissure
    - corpus callosum
  - **Association pathways**: pathways connecting cortical regions to cortical regions
    - arcuate fasciculus (AF), frontal aslant (FAT), superior longitudinal fasciculus (SLF) II, III
    - cingulum (frontal parahippocampal, frontal parietal, parahippocampal parietal, parahippocampal, and parolfactory), superior longitudinal fasciculus (SLF) I
    - inferior fronto-occipital fasciculus (IFOF), uncinate fasciculus (UF)
    - inferior longitudinal fasciculus (ILF), middle longitudinal fasciculus (MdLF), vertical occipital fasciculus (VOF), temporo-parietal aslant tract, extreme capsule.

<img src="https://user-images.githubusercontent.com/275569/190517156-b6da60eb-e7fd-47e9-872f-a73b08c3d1e2.png" width=500>

<img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41467-022-32595-4/MediaObjects/41467_2022_32595_Fig3_HTML.png?as=webp" width=700>

source: [Nature communications. 2022 Aug 22;13(1):1-3.](https://www.nature.com/articles/s41467-022-32595-4)


  - **Projection pathways**: pathways connecting cortical regions to the basal ganglia or brain stem nuclei
    - thalamus: thalamic radiation (anterior, posterior and superior), acoustic radiation, optic radiation, dentatorubrothalamic tract (DRTT), medial lemniscus    
    - striatum: corticostriatal tract (anterior, superior, and posterior), fornix
    - brain stem nuclei: corticospinal tract,  reticulospinal tract, corticobulbar tract, corticopontine tract (frontal, parietal, and occipital),  
  - Cerebellum pathways, brainstem pathways, cranial nerves  
      
  - White matter regions (not pathways)
    - internal capsule
    - corona radiata  
    - centrum semiovale  
      
### Virtual dissection (20 min)

- Tract menu
  - Tract editing and [shortcuts](https://dsi-studio.labsolver.org/doc/gui_t3_visualization.html#shortcuts-and-graphic-control)
  - Virtual dissection [[document]](https://dsi-studio.labsolver.org/doc/gui_t3_whole_brain.html)
    - Difficulty level (easy): commissural pathways
    - Difficulty level (medium): association pathways
    - Difficulty level (hard): projection pathways
  - Region-based filtering

<iframe width="896" height="504" src="https://www.youtube.com/embed/1xfhaFQhCtY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Automatic Fiber Tracking (10 min)

- Automatic fiber tracking [[document]](https://dsi-studio.labsolver.org/doc/gui_t3_atk.html)
   
<iframe width="896" height="504" src="https://www.youtube.com/embed/Hzeb_q6ux-Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Assignment: Download FIB file

1. Download [100206.src.gz.gqi.1.7.fib.gz](https://zenodo.org/record/6307812/files/100206.src.gz.gqi.1.7.fib.gz?download=1) and [100206_T1w.nii.gz](https://pitt-my.sharepoint.com/:u:/g/personal/yehfc_pitt_edu/ET42Z4taJRtKrxvYKmEHZiIBJHdng-G-YyyHQjYCwM7vRg?e=Rjk7sA)

2. Open the FIB file using [Step T3 Fiber Tracking] and click on [Step T3d Tracts][Fiber Tracking] to generate whole brain tracts.

  - [Optional] check out [document](https://dsi-studio.labsolver.org/doc/gui_t3_whole_brain.html) and test different fiber tracking parameters. Observe how changing them leads to different results.
  
3. Manually segment **left arcuate fasciculus**, **cingulum**, **uncinate fasciculus**, **corticospinal tract** from whole brain tracks. Compare it with automatic tracking results.

4. Segment left arcuate fasciculus into the acoustic, visual, and lexical encoding part and assign different colors (reference: Giampiccolo D, Duffau H. Controversy over the temporal cortical terminations of the left arcuate fasciculus: a reappraisal. Brain. 2022 Feb 10.)

![image](https://user-images.githubusercontent.com/275569/165971411-eeab4e61-f356-4456-b582-627a05f778da.png)

(Giampiccolo et al. 2022)

<img src="https://user-images.githubusercontent.com/275569/165971142-40f86637-b727-47da-9e8d-2ffa2338f70f.png" width=500>
(Segmented on HCP1065 tractography atlas)



