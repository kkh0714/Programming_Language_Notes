### <u>Anaconda Menu & Create Virtual Enviornment</u>

Install Package:

1. Click Start → Search Anaconda Prompt
2. ```
   conda install numpy
   ```

Create and Activate New Environment:
1. Click Start → Search Anaconda Prompt
2. ```
   conda create -n myenv python=3.10
   ```
3. ```
   conda activate myenv
   ```

Current Environment Available:
1. ml311_env (python 3.11 with CUDA 12.4) for project **SQL-Query-Generation-with-LoRA-Fine-tuned-CodeLlama**

-- Note: the compatibility between torch and CUDA 12.4 may rely on the latest version of torch. Better search for Pytorch official website to check which build is stable https://pytorch.org/get-started/locally/.



Create Virtual Environment without conda:

```bash
# Create virtual environment
python3.11 -m venv venv

# Check the python version 
python --version

# Activate it
# On Windows:
venv\Scripts\activate
# On Windows(bash)
source venv/Scripts/activate
# On macOS/Linux:
source venv/bin/activate

# Install your dependencies
pip install -r requirements.txt  # if you have one
# or install GPU-specific packages
pip install tensorflow-gpu  # or pytorch with CUDA, etc.

# Deactivate
deactivate

# Remove the venv
rm -rf venv
```

=========================================================================================================

### <u>Mobile App Notes</u>

Create React Native setup:

1\. npx create-expo-app MyApp (start with example components and src)

2\. npx @react-native-community/cli init MyApp (start from scratch)



Start emulator:

1\. npx expo start (open web)

2\. press a (open android emulator)



Check Expo (EAS) credentials:

eas credentials

&nbsp;- it shows different credentials, i.e. SHA1 = 12:34:56:78:90:AB:CD:EF:12:34:56:78:90:AB:CD:EF:12:34:56:78

&nbsp;- SHA1 is used for Google API setting "Application restrictions" for Android

=========================================================================================================

### <u>**Machine Learning Dependencies**</u>

1\. numpy

2\. scipy

3\. pandas

4\. nltk

5\. scikit-learn

6\. scikit-image

7\. (genism)

8\. tensorflow/pytorch

9\. (opencv)

10\. (pillow)

=========================================================================================================
