## LLM4BeSci at GSERM2024

The course introduces the use of open-source large language models (LLMs) from the Hugging Face ecosystem for research in the behavioral and social sciences. 

By [Dirk Wulff](https://www.mpib-berlin.mpg.de/person/93374/2549) and [Zak Hussain](https://zak-hussain.github.io/)

### Schedule

#### Day 1
<font style="font-size:10">09:15 AM - 09:45 AM: Welcome & Intro<br>
09:45 AM - 10:45 AM: [Talk: Intro to LLMs](day_1/day_1.pdf)<br>
10:45 AM - 11:00 AM: Break<br>
11:00 AM - 12:00 PM: Discussion: Find applications in small groups<br>
12:00 PM - 01:00 PM: Lunch<br>
01:00 PM - 02:00 PM: [Talk: A gentle intro to Hugging Face and Python](day_1/day_1_hf.pdf)<br>
02:00 PM - 02:15 PM: Setup Colab<br>
02:15 PM - 02:45 PM: [Exercise: Running pipelines](day_1/day_1.ipynb)<br>
02:45 PM - 03:15 PM: Walkthrough<br>

#### Day 2
09:15 AM - 09:45 AM: Recap quiz<br>
09:45 AM - 10:45 AM: [Talk: Intro to transformers & embeddings](day_2/day_2.pdf)<br>
10:45 AM - 11:00 AM: Break<br>
11:00 AM - 12:00 PM: [Talk: Intro to transformers & embeddings (continued)](day_2/day_2.pdf)<br>
12:00 PM - 01:00 PM: Lunch<br>
01:00 PM - 02:00 PM: [Exercise: Clarifying personality psychology](day_2/day_2.ipynb)<br>
02:00 PM - 02:30 PM: Walkthrough<br>
02:30 PM - 03:15 PM: Discussion: Find applications in small groups<br>

#### Day 3
09:15 AM - 09:45 AM: Recap quiz<br>
09:45 AM - 10:45 AM: [Intro to classification and regression](day_3/day_3.pdf)<br>
10:45 AM - 11:00 AM: Break<br>
11:00 AM - 12:00 PM: [Exercise: Classifying media bias w/ zero & few-shot](day_3/day_3a.ipynb)<br>
12:00 PM - 01:00 PM: Lunch<br>
01:00 PM - 02:00 PM: [Exercise: Classifying media bias w/ fine-tuning](day_3/day_3b.ipynb)<br>
02:00 PM - 02:30 PM: Walkthrough<br>
02:30 PM - 03:15 PM: Discussion: Find applications in small groups<br>

#### Day 4
09:15 AM - 09:45 AM: Recap quiz<br>
09:45 AM - 10:45 AM: [Intro to text generation & synthetic participants](day_4/day_4.pdf)<br>
10:45 AM - 11:00 AM: Break<br>
11:00 AM - 12:00 PM: [Exercise: Numeracy](day_4/day_4a.ipynb)<br>
12:00 PM - 01:00 PM: Lunch<br>
01:00 PM - 02:00 PM: [Exercise: Steering vaccine hesitancy response](day_4/day_4a.ipynb)<br>
02:00 PM - 02:30 PM: Walkthrough<br>
02:30 PM - 03:15 PM: Discussion: Find applications in small groups<br>

#### Day 5
09:15 AM - 09:45 AM: Recap quiz<br>
09:45 AM - 10:45 AM: [Talk: Intro to qualitative data analysis](day_5/day_5.pdf)<br>
10:45 AM - 11:00 AM: Break<br>
11:00 AM - 12:00 PM: [Exercise: Article and interview Q&A](day_5/day_5.ipynb)<br>
12:00 PM - 01:00 PM: Lunch<br>
01:00 PM - 03:00 PM: Project pitches<br>
03:00 PM - 03:15 PM: Wrap up<br>

### Examination
The course grade will be determined based on the quality of a project pitch at the end of the course and a two-page research paper submitted after the course. The paper communicates an analysis applying large language models to a personal research question, including all parts of a traditional research paper (introduction, method, results, and discussion). The research paper can be based on the examples during the course. The research paper must be submitted via mail (wulff at mpib-berlin.mpg.de) by June 28th. To enroll for the research paper send us the slides of your project sketch presentation via mail immediately after the conclusion of the course.      



### Resources
<a href="https://osf.io/preprints/psyarxiv/f7stn">Hussain, Binz, Mata, & Wulff (2024) A tutorial on open-source large language models for behavioral science
</a>
```@misc{hussain_binz_mata_wulff_2023,
 title={A tutorial on open-source large language models for behavioral science},
 url={osf.io/preprints/psyarxiv/f7stn},
 publisher={PsyArXiv},
 author={Hussain, Zak and Binz, Marcel and Mata, Rui and Wulff, Dirk U},
 year={2023},
 month={Dec},
 doi={https://doi.org/10.31234/osf.io/f7stn}
}
```

[Hugging face documentation](https://huggingface.co/docs)<br>
[Hugging face book](https://transformersbook.com/)<br>
[But what is a GPT (3Blue1Brown)](https://www.youtube.com/watch?v=wjZofJX0v4M&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=5)<br>

### Installation Instructions
0. If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
1. Navigate to Google Drive (https://drive.google.com/).
2. In the top-left, click New > More > Colaboratory. If you do not see Colaboratory, you may need to click "Connect more apps", 
search for 'Colaboratory', and install it. Then click New > More > Colaboratory.
3. Copy the following code snipped into the first cell of the notebook. Run it (```shift + enter``` or click &#9658; button) to mount your Google Drive to the Colab environment.
A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab (you will have to do this
every time you open a new notebook).
```
from google.colab import drive
drive.mount("/content/drive")
```
4. Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to clone the GitHub repository to your Google Drive :
```
%cd /content/drive/MyDrive
!git clone https://github.com/Zak-Hussain/LLM4BeSci_GSERM2024.git
```
5. Go back to your Google Drive and navigate to the folder "LLM4SocBeSci". You should see the directories `day_1`, `day_2`,`day_3`, `day_4`, and `day_5` containing the relevant notebooks (.ipynb files) and data (it may take  a couple of minutes for the files to appear) for the exercises of each day.
6. Open the folder `day_1` and then the `day_1.ipynb` notebook. A new Colab window will open.
7. Run the first cell of the notebook to install the required packages. This may take a few minutes and ask for you to give permission to access your Google Drive. 

You are now ready to start the exercises!
