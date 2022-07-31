# NER Plant-Disease Dataset

## <img src="https://img.icons8.com/external-smashingstocks-flat-smashing-stocks/64/000000/external-manager-hotel-smashingstocks-flat-smashing-stocks-2.png"/> **`Slamet Riyanto S.Kom., M.M.S.I.`**

## <img src="https://img.icons8.com/external-fauzidea-flat-fauzidea/64/undefined/external-man-avatar-avatar-fauzidea-flat-fauzidea.png"/> **`Dimas Dwi Putra`**

## Original
## [National Center for Biotechnology Information (NCBI)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6713337/) 

## Annotated
```yaml
"Studies on magnesium's mechanism of action in <ENAMEX TYPE="plant">digitalis</ENAMEX> -induced <ENAMEX TYPE="disease">arrhythmias</ENAMEX> ."
```

## B-I-O
```yaml
studies	O
on	O
magnesium s	O
mechanism	O
of	O
action	O
in	O
digitalis	B-plant
induced	O
arrhythmias	B-disease
```

## Json
```yaml
{
  "id": 447, 
  "text": "studies on magnesium s mechanism of action in digitalis induced arrhythmias", 
  "labels": [
    ["T0", "plant", 46, 55, "digitalis"], 
    ["T1", "disease", 64, 75, "arrhythmias"]
  ]
}
```

## Excel / CSV + NLTK POS Tagging

| Sentence #  | Word        | POS | Tag       |
| ----------- | ----------- | --- | --------- |
| Sentence: 0 | studies     | NNS | O         |
| Sentence: 0 | on          | IN  | O         |
| Sentence: 0 | magnesium   | NN  | O         |
| Sentence: 0 | s           | NN  | O         |
| Sentence: 0 | mechanism   | NN  | O         |
| Sentence: 0 | of          | IN  | O         |
| Sentence: 0 | action      | NN  | O         |
| Sentence: 0 | in          | IN  | O         |
| Sentence: 0 | digitalis   | NN  | B-plant   |
| Sentence: 0 | induced     | VBD | O         |
| Sentence: 0 | arrhythmias | NNS | B-disease |

# **Other Content**

### **Websites Prediction**
#### [1. Django Websites Prediction For NER dan RE](https://github.com/Dimas263/Django-Websites_NER_RE)


### **Named Entity Recognition (NER)**
#### [1. NER Dataset Biomedical Plant-Disease Corpus](https://github.com/Dimas263/NLP_NER_Dataset_Biomedical_Plant-Disease_Corpus)
#### [2. NER CRF Named Entity Recognition](https://github.com/Dimas263/NLP_NER_CRF_Named_Entity_Recognition)
#### [3. NER BiLSTM Named Entity Recognition](https://github.com/Dimas263/NLP_NER_BILSTM_Named_Entity_Recognition)
#### [4. NER BERT Named Entity Recognition](https://github.com/Dimas263/NLP_NER_BERT_Named_Entity_Recognition)
#### [5. NER BiLSTM CRF Named Entity Recognition](https://github.com/Dimas263/NLP_NER_BILSTM_CRF_Named_Entity_Recognition)
#### [6. NER BERT BiLSTM CRF Named Entity Recognition](https://github.com/Dimas263/NLP_NER_BERT_BILSTM_CRF_Named_Entity_Recognition)


### **Relation Extraction (NER)**
#### [1. RE Dataset Biomedical Plant-Disease Corpus](https://github.com/Dimas263/NLP_RE_Dataset_Biomedical_Plant-Disease_Corpus)
#### [2. RE BERT Relation Extraction Biomedical](https://github.com/Dimas263/NLP_RE_BERT_Relation_Extraction_Biomedical)
#### [3. RE BiLSTM CRF Relation Extraction Biomedical](https://github.com/Dimas263/NLP_RE_BILSTM_CRF_Relation_Extraction_Biomedical)
