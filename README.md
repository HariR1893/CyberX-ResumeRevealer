# CyberX-ResumeRevealer

ResumeRevealer is an advanced tool designed for HR professionals, recruiters, and hiring managers to streamline the process of resume parsing and candidate evaluation. It offers a comprehensive solution to extract valuable insights from diverse resume formats, standardize job titles, and mine detailed skills from project descriptions.

## **Key Features:**

**Resume Parsing:** Automatically extracts key information from resumes in various formats including PDF, DOCX, and HTML.

**Job Title Standardization:** Utilizes the O-NET database to standardize job titles and occupations for consistent taxonomy.

**Skill Extraction:** Mines detailed skills from project descriptions using advanced Natural Language Processing (NLP) techniques.

**Resume Section Identification:** Uses Named Entity Recognition (NER) to accurately identify and classify resume sections such as experience, education, skills, and more.

### **Who It's For:**

**HR Professionals:**
 Simplifies the screening process by providing accurate and standardized information about candidates.

**Recruiters:** Enables quick and efficient evaluation of candidate profiles, saving time and effort.

**Hiring Managers:** Facilitates better decision-making by presenting detailed insights into candidate skills and experiences.

## Screenshots

### **Text Extraction**

![Resume Text Extraction](https://github.com/HariR1893/CyberX-ResumeRevealer/blob/main/assets/text-extraction.png)

### **Resume Section**

![Resume Text Extraction](https://github.com/HariR1893/CyberX-ResumeRevealer/blob/main/assets/resume-section.png)

### **Find Job Title**

![Resume Text Extraction](https://github.com/HariR1893/CyberX-ResumeRevealer/blob/main/assets/jobtitle.png)

### **Find ONET-Occupation**

![Resume Text Extraction](https://github.com/HariR1893/CyberX-ResumeRevealer/blob/main/assets/onet-occupation.png)

### **Extract Skills from Porject Description**

![Resume Text Extraction](https://github.com/HariR1893/CyberX-ResumeRevealer/blob/main/assets/skills-proj-desp.png)

## Demo

https://github.com/HariR1893/CyberX-ResumeRevealer/assets/84437531/c30d47a2-1e1f-44ab-b63f-a9f853b50fc2


## Installation

Install ResumeRevealer with python >= 3.9

> Tested on python 3.11

```bash
  git clone https://github.com/HariR1893/CyberX-ResumeRevealer.git
  cd CyberX-ResumeRevealer
```

Install the requirements.

```bash
  pip install -r requirements.txt
```

Download the Custom trained NER Model:
> Download the pre-trained model -> [click here](https://drive.google.com/drive/folders/1hX-Lx1Q7yRV1kPSXvgRyBgB_WEMnz0aw?usp=sharing)
> save it in a :
> ```models/ner/JdModel```

### *Run*

```toolkit.ipynb```
