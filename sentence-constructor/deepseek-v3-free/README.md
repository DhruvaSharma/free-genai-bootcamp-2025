## DeepSeek Powered Assistant Guide
### Which Model
Deepseek is using DeepSeek-V3 671B

https://ollama.com/library/deepseek-v3

# Guide to Providing Examples in a Prompt Document for DeepSeek

When creating a prompt document for DeepSeek or any AI model, providing clear and structured examples is crucial for guiding the model to generate the desired output. Below is a recommended format for including examples in your prompt document.

---

## **Format for Providing Examples in a Prompt Document**

### 1. **Objective**  
Clearly state the goal of the task or the type of output you want the model to generate.  

**Example**:  
*"Translate the following English sentences into Japanese. Use appropriate particles and verb conjugations."*

---

### 2. **Instructions**  
Provide specific instructions or rules the model should follow.  

**Examples**:  
- *"Do not include particles in the vocabulary list."*  
- *"Use dictionary forms for verbs and nouns."*  
- *"Provide a vocabulary table and a possible sentence structure."*

---

### 3. **Examples**  
Include a few examples of input-output pairs to demonstrate the desired format and style. Each example should follow this structure:  

#### Example 1:  
- **Input**: *"The cat is on the table."*  
- **Output**:  
  - **Vocabulary Table**:  
    | Japanese | Romaji | English |  
    |----------|--------|---------|  
    | 猫       | neko   | cat     |  
    | テーブル | teeburu| table   |  
    | いる     | iru    | to be   |  
  - **Sentence Structure**:  
    猫 が テーブル に いる。  

#### Example 2:  
- **Input**: *"Did you eat the apple?"*  
- **Output**:  
  - **Vocabulary Table**:  
    | Japanese | Romaji | English |  
    |----------|--------|---------|  
    | 食べる   | taberu | to eat  |  
    | りんご   | ringo  | apple   |  
  - **Sentence Structure**:  
    りんご を 食べた か。  

---

### 4. **Notes**  
Add any additional notes or clarifications to help the model understand the task better.  

**Examples**:  
- *"The student needs to figure out the correct particles and conjugations, so do not provide them in the output."*  
- *"Use only dictionary forms for verbs and nouns in the vocabulary table."*

---

### 5. **Student Input**  
Provide a placeholder or example for the student's input.  

**Example**:  
- **Student Input**: *"Bears are at the door, did you leave the garbage out?"*

---

## **Why This Format Works**
- **Clarity**: The objective and instructions are clearly stated, reducing ambiguity.  
- **Structure**: Examples are presented in a consistent format, making it easy for the model to follow.  
- **Guidance**: Notes and additional instructions help the model understand the constraints and requirements.  

---

## **Example Prompt Document**

### **Objective**:  
Translate the following English sentences into Japanese. Use appropriate particles and verb conjugations.  

### **Instructions**:  
1. Do not include particles in the vocabulary list.  
2. Use dictionary forms for verbs and nouns.  
3. Provide a vocabulary table and a possible sentence structure.  

### **Examples**:  

#### Example 1:  
- **Input**: *"The cat is on the table."*  
  - **Output**:  
    - **Vocabulary Table**:  
      | Japanese | Romaji | English |  
      |----------|--------|---------|  
      | 猫       | neko   | cat     |  
      | テーブル | teeburu| table   |  
      | いる     | iru    | to be   |  
    - **Sentence Structure**:  
      猫 が テーブル に いる。  

#### Example 2:  
- **Input**: *"Did you eat the apple?"*  
  - **Output**:  
    - **Vocabulary Table**:  
      | Japanese | Romaji | English |  
      |----------|--------|---------|  
      | 食べる   | taberu | to eat  |  
      | りんご   | ringo  | apple   |  
    - **Sentence Structure**:  
      りんご を 食べた か。  

### **Notes**:  
- The student needs to figure out the correct particles and conjugations, so do not provide them in the output.  
- Use only dictionary forms for verbs and nouns in the vocabulary table.  

### **Student Input**:  
*"Bears are at the door, did you leave the garbage out?"*  

---

This format ensures that the model understands the task and generates outputs that align with your expectations. Let me know if you need further assistance!