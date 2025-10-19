# Tamil TTS Evaluation Project

Welcome to the **Tamil Text to Speech (TTS) Comparison Project** repository. This project was part of my Bachelor's thesis on evaluating existing TTS tools for the Tamil language. It contains all the necessary code, datasets, and evaluation scripts for generating/creating synthesized speech output learning materials and analyzing it using objective and subjective metrics.

---

## Project Overview

The main goal of this project is to **analyze the performance of different Tamil TTS tools** and compare their outputs to human reference speech. The evaluation includes:

* **Text-to-Speech Generation** using 6 TTS tools
  
* **Objective Metrics:**

  * **Word Error Rate (WER)**
  * **Mel-Cepstral Distortion (MCD)**
  * **F0 Root Mean Square Error (F0 RMSE)**
    
* **Subjective Metrics:**

  * **Comparative Mean Opinion Score (CMOS)** 

The project also includes all datasets used for testing the TTS and the evaluation data collected from 30 participants.

---

## Tools and Technologies

* **Programming Language:** Python 3.12
  
* **TTS Models:**

  * Meta’s MMS-TTS
  * Google TTS
  * eSpeak
  * IndicTTS
  * gTTS
  * Bhashini TTS
  
* **Libraries:**
  `transformers`, `torch`, `librosa`, `numpy`, `scipy`, `pandas`, `seaborn`, `matplotlib`, `whisper`
  
* **Data Analysis & Visualization:** Pandas, Matplotlib, Seaborn :)

---

## Usage

1. **TTS Generation**

   * Use the scripts in `/TTS tools` to generate speech from text or CSV datasets.
  
2. **Objective Evaluation**

   * Run the scripts in `/Evalution metrics` to calculate WER, MCD, and F0 RMSE for synthesized speech.

3. **Subjective Evaluation**

   * Use `Dataset/CMOS/cmos_analysis.py` to analyze human evaluation scores and visualize the results.

---

## Datasets

1. **Tamil Learning Material Dataset** – It has 90 text input learning materials used for TTS audio generation.
2. **CMOS Evaluation Dataset** – It contains 30 participant's ratings for subjective evaluation of TTS systems.

---

## Citation

If you use this dataset or scripts for research, you can cite as ;)

```
Sujai Shanmugam. (2026). "COMPARATIVE ANALYSIS OF TEXT TO SPEECH TOOLS FOR CREATING LEARNING MATERIALS IN TAMIL LANGUAGE", Bachelor's Thesis, RTU: Riga, Latvia, 2026.
```

---

## Notes

* Make sure all Python dependencies are installed:

  ```bash
  pip install -r requirements.txt
  ```
* The TTS scripts require internet access for some models (e.g., gTTS, Google Cloud TTS).
* Audio outputs are saved in `results/generated_audio/`.

---

## Contact

For questions or suggestions, feel free to reach out: **[sujai.shanmugam@edu.rtu.lv](mailto:sujai.shanmugam@edu.rtu.lv)**

---

## Acknowledgements

I would like to thank to my scientific adviser **Dr.sc.ing., Associate Professor Egons Lavendiels** for his guidance and support throughout this bachelor thesis.  

And, the special thanks to my Tamil teacher **S. Managalam, M.Sc. Tamil Literature** for providing the female speech reference recordings, which were used for evaluating the Tamil output results.

Last but not least, really big thanks to **Ahrane Mahaganapthy** for her continuous feedback, helping to clarify doubts, and providing valuable suggestions for this bachelor thesis! 
