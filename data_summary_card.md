 

# Data Summary for microsoft/mattergen 

 

 

## 1. General information 

**1.0.1 Version of the Summary:** 1.0 

 

**1.0.2 Last update:** 04-Dec-2025 

 

## 1.1 Model Developer Identification 

**1.1.1 Model Developer name and contact details:** Microsoft Corporation at One Microsoft Way, Redmond, WA 98052. Tel: 425-882-8080 

 

## 1.2 Model Identification 

**1.2.1 Versioned model name(s):** MatterGen 

 

**1.2.2 Model release date:** 16-Jan-2025 

 

## 1.3 Overall training data size and characteristics 

### 1.3.1 Size of dataset and characteristics 

**1.3.1.A Text training data size:** Not applicable. Text data is not part of the training data 

 

**1.3.1.B Text training data content:** Not applicable 

 

**1.3.1.C Image training data size:** Not applicable. Images are not part of the training data 

 

**1.3.1.D Image training data content:** Not applicable 

 

**1.3.1.E Audio training data size:** Not applicable. Audio data is not part of the training data 

 

**1.3.1.F Audio training data content:** Not applicable 

 

**1.3.1.G Video training data size:** Not applicable. Video data is not part of the training data   

 

**1.3.1.H Video training data content:** Not applicable 

 

 

 

**1.3.1.I Other training data size:** 607,684 crystal structures 

 

**1.3.1.J Other training data content:** DFT-relaxed inorganic crystal structures (unit cell lattices, atomic fractional coordinates, and element types) from Materials Project (v2022.10.28) and Alexandria; filtered to energy above hull < 0.1 eV/atom, excluding noble gases and elements with Z>84 or Tc, Pm. 

 

**1.3.2 Latest date of data acquisition/collection for model training:** 18-Aug-2023 

 

**1.3.3 Is data collection ongoing to update the model with new data collection after deployment?** No 

 

**1.3.4 Date the training dataset was first used to train the model:** 18-Aug-2023 

 

**1.3.5 Rationale or purpose of data selection:** Datasets of DFT-relaxed inorganic crystalline materials were selected to train a diffusion model that jointly generates atomic coordinates, element types, and unit cell lattices for stable materials across the periodic table. Filtering to structures within 0.1 eV/atom above reference convex hull emphasizes stability, while excluding certain elements and limiting to ≤20 atoms targets the intended model scope and computational feasibility 

 

## 2. List of data sources 

### 2.1 Publicly available datasets 

**2.1.1 Have you used publicly available datasets to train the model?** Yes 

 

## 2.2 Private non-publicly available datasets obtained from third parties 

### 2.2.1 Datasets commercially licensed by rights holders or their representatives 

**2.2.1.A Have you concluded transactional commercial licensing agreement(s) with rights holder(s) or with their representatives?** Not applicable 

 

### 2.2.2 Private datasets obtained from other third-parties 

**2.2.2.A Have you obtained private datasets from third parties that are not licensed as described in Section 2.2.1, such as data obtained from providers of private databases, or data intermediaries?** No 

 

## 2.3 Personal Information 

**2.3.1 Was personal data used to train the model?** Microsoft follows all relevant laws and regulations pertaining to personal information 

 

## 2.4 Synthetic data 

**2.4.1 Was any synthetic AI-generated data used to train the model?** No 

 

## 3. Data processing aspects 

### 3.1 Respect of reservation of rights from text and data mining exception or limitation 

**3.1.1 Does this dataset include any data protected by copyright, trademark, or patent?** Microsoft follows all required regulations and laws for processing data protected by copyright, trademark, or patent 

 

## 3.2 Other information 

**3.2.1 Does the dataset include information about consumer groups without revealing individual consumer identities?** Microsoft follows all required regulations and laws for protecting consumer identities 

 

**3.2.2 Was the dataset cleaned or modified before model training?** Yes 

 

 