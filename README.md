# THOS
THOS: A Benchmark Dataset for Targeted Hate and Offensive Speech
================================================================

**Description**:
THOS is a benchmark dataset that contains 8282 tweets that have been annotated by experts for hate speech and offensive language. Please refer to [THOS paper](https://dmlr.ai/assets/accepted-papers/34/CameraReady/DMLR_ICML23%20(28).pdf) for more details.

THOS dataset contains different label categories.
1. **Speech Type**: Columns #2 and #3. The columns indicate whether the text is normal, only hate (implicit hate speech), only offensive, or both (explicit hate speech) hate and offensive.
2. **Topics**: Columns 4-9 represent the high level speech's targets (i.e. Country, Religion, Ethnicity/Race, Politics, Other, Individual).
3. **Sub-topics**: Columns 10-41 represent low-level speech's targets (i.e. groups within each of the aforementioned topics).


Please cite:

~~~
@inproceedings{SaadAlmohaimeed-2023-DMLR,
  author = {Saad Almohaimeed, Saleh Almohaimeed, Ashfaq Ali Shafin, Bogdan Carbunar, Ladislau Bölöni},
  title = "{THOS}: A Benchmark Dataset for Targeted Hate and Offensive Speech",
  year = "2023",
  month = "July",
  booktitle = "Proc. of Data-centric Machine Learning Research (DMLR) Workshop at ICML 2023",
  doi              = "10.48550/arXiv.2311.06446"
}
~~~
