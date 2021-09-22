# GEMINI follow-along hands-on workshop

## open this URL :

https://gemini-dpuru-debugpoint136.vercel.app

### Copy this view region

```bash
chr7:516248-27213582
```

![Remote g3d track](img/1.png 'Remote g3d track')

This is how it looks like after initial load of a g3d track:

![Remote g3d view](img/2.png 'Remote g3d view')

## Configure visualization

Click the **Open menu** button to open the configuration menu.

### configure resolution/model/layout

The top of the menu allows you to control resulution, model and layout settings.

![model control](img/3.png 'model control')

### change highlighting/add labels

By default the 3D viewer highlights the region in current browser widow. Zoom in/out will update the highlight area.

![highlight menu](img/4.png 'highlight menu')
![highlight menu](img/5.png 'highlight menu')

View style can be customized by changing the color, opacity and thickness settings:

![highlight example](img/demo4.png 'highlight example')

### features to try out

# Features

- Browser - load data
- smaller region - `chr7:21874114-32553048`
- [x] Track Selection
- [ ] Input Data structure
- [ ] Render
- [ ] Radius Selection
- [ ] BPS
- [ ] Download the Search result
- [ ] Save to Genome
- [ ] Bigger Region with arc view - `chr7:103212734-124515672`
- [ ] Preserve Selection - Union
- [ ] Conform Selection - Intersection
- [ ] Volume Selection
- [ ] Radius Selection
- [ ] Section Selection
- [ ] Gene Search
- [ ] Abstraction - Hide and show
- [ ] Console
- [ ] Add annotation
- [ ] Radius highlight
- [ ] Volume highlight
- [ ] Export
- [ ] Open in Castor
- [ ] Save View Recall
- [ ] Live Session

| Feature                                                  | Description                                               |
| -------------------------------------------------------- | --------------------------------------------------------- |
| Live Session                                             | customized 4 column bed color file                        |
| loop22.bed                                               | bed file with loop positions                              |
| domains_nooverlap.bed                                    | bed file with domain positions                            |
| E003_15_coreMarks_dense.bed                              | chomHMM annotation                                        |
| 486778af-8f8e-4000-9812-409604e274a5.FPKM.cordinates.txt | gene expression results                                   |
| refGene.txt.gz                                           | refGene annotation from UCSC                              |
| regionlist.txt                                           | a text file contain a list of regions, one region per row |
| custom.colors.bed                                        | customized 4 column bed color file                        |
| 4DNFI4G2OZOI.txt                                         | A/B compartment annotation from 4DN                       |
| GSE63525_GM12878_subcompartments.bed                     | 6 compartment annotation from Rao et. al                  |
| GSE63525_GM12878_subcompartments.bed.gz                  | same as above but in gzipped format                       |

### add labels

Input gene symbol or genomic region for single labeling. Upload a file containing regions (for example `regionlist.txt`) for batch labeling.

![labeling example](img/demo6.png 'labeling example')

### export model

Under the Export section there are 2 buttons allow users to save the main and thumbnail stucture, respectively.
