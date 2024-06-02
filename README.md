<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">YOLOv10 - Document Layout Analysis</h3>

  <p align="center">
    Trained on DocLayNet dataset
    <br />
    <a href="https://huggingface.co/spaces/linhdo/document-layout-analysis">Live HuggingFace Demo</a>
    ·
    <a href="https://github.com/LynnHaDo/Document-Layout-Analysis/issues">Visit YOLOv10</a>
    ·
    <a href="https://github.com/LynnHaDo/Document-Layout-Analysis/issues">Request Feature or Report Problem</a>
  </p>
</div>

<!-- UPDATES -->
## Updates 

I have trained in this project YOLOv10 on DocLayNet dataset. Below you see results table. Feel free to use our fine-tuned models and don't forget to cite YOLOv10, DocLayNet and our repository. Don't forget to give this repo a 🌟!

 * 02/06/2024: HugginFace demo is live with Yolov10-x model best weights.
 * 
<!-- ABOUT THE PROJECT -->
## About The Project

Due to the lack of computational resources, I only performed the training process on the Doclaynet-base dataset which contains 6910 train images, 648 val images, 499 test images. However, the model could perform relatively well, further proving the superiority of YOLOv8 model. 

<img src="images/samples.gif" height=640 align = "center"/>

### Built With

* [YOLOv10](https://ultralytics.com/yolov8)
* [Hugging Face Spaces](https://huggingface.co/spaces)
* [Gradio](https://www.gradio.app/)

<!-- GETTING STARTED -->
### Prerequisites

1. python 3
2. ultralytics
3. numpy
4. opencv-python

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/LynnHaDo/Document-Layout-Analysis.git
   ```
2. Install packages
   ```sh
   pip install ultralytics
   pip install numpy
   pip install opencv-python
   ```
3. Download [Doclaynet dataset](https://huggingface.co/datasets/ds4sd/DocLayNet) and save it as ```datasets/doclaynet-base``` 
4. (Optional) Download [pretrained YOLOv8s weights](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8s.pt)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Works Cited -->
## Works Cited

1. Ultralytics YOLOv8
   
   ```sh
   authors:
    - family-names: Jocher
      given-names: Glenn
      orcid: "https://orcid.org/0000-0001-5950-6979"
    - family-names: Chaurasia
      given-names: Ayush
      orcid: "https://orcid.org/0000-0002-7603-6750"
    - family-names: Qiu
      given-names: Jing
      orcid: "https://orcid.org/0000-0003-3783-7069"
   title: "YOLO by Ultralytics"
   version: 8.0.0
   date-released: 2023-1-10
   license: AGPL-3.0
   url: "https://github.com/ultralytics/ultralytics"
   ```
   
2. Doclaynet-base dataset

   ```sh
   @article{doclaynet2022,
    title = {DocLayNet: A Large Human-Annotated Dataset for Document-Layout Segmentation},
    doi = {10.1145/3534678.353904},
    url = {https://doi.org/10.1145/3534678.3539043},
    author = {Pfitzmann, Birgit and Auer, Christoph and Dolfi, Michele and Nassar, Ahmed S and Staar, Peter W J},
    year = {2022},
    isbn = {9781450393850},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    booktitle = {Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
    pages = {3743–3751},
    numpages = {9},
    location = {Washington DC, USA},
    series = {KDD '22}
    }
   ```

<!-- CONTACT -->
## Contact

Linh Do - do24l@mtholyoke.edu/dohalinh2303@gmail.com (personal)

Project Link: [https://github.com/LynnHaDo/Document-Layout-Analysis](https://github.com/LynnHaDo/Document-Layout-Analysis)

LinkedIn: [https://linkedin.com/in/Linh Do](https://www.linkedin.com/in/linh-do-0327371b2/)

<p align="right">(<a href="#top">back to top</a>)</p>
