# 504_serverless_functions-
Implementation of HTTP Serverless Function

# Lab Rules
A creatinine test is a measure of how well the kidneys are doing their job of filtering waste from the blood.
Creatinine is a chemical compound left over from energy-making processes in muscles. Healthy kidneys filter creatinine out of the blood. Creatinine exits the body as a waste product in urine.
A measurement of creatinine in your blood or urine helps your healthcare professional find out how well your kidneys are working.

**Serum creatinine** is reported as milligrams of creatinine to a deciliter of blood (mg/dL). Or it's reported as micromoles of creatinine to a liter of blood (µmol/L). 

### The typical range for serum creatinine is:

**For adult men, 0.74 to 1.35 mg/dL (65.4 to 119.3 µmol/L)**

**For adult women, 0.59 to 1.04 mg/dL (52.2 to 91.9 µmol/L)**

<img src="https://cms-img.coverfox.com/Normal-Creatinine-Level-Ranges.jpeg" alt="Creatinine Level Chart" width="400"/>

# Cloud Environment
- Google Cloud Platform
  - Region: europe-west1 (Belgium)
- Microsoft Azure
  - Region: West US 3
- Colab
  - Used to run Python code

# Deployment Commands
## GCP
### Step 1: Go To Cloud Run
### Step 2: Click Deploy Container
### Step 3: Choose Deployment Method:
  - Click Function
    - "Use an inline editor to create a function"
    - Pick the language/runtime (Python 3.13)
### Step 4: Set Service Settings
  - Service name : creatinine-value
  - Region: europe-west1 (Belgium)
  - Authentification: "Allow Public Access" if you want a public URL anyone can access
  - Auto Scaling: Maximum instance "1"
### Step 5: Create
- Google will build and deploy your code
- After a minute or so, you’ll get a live URL to your deployed service!

## Azure
### Step 1:
### Step 2:
### Step 3:
### Step 4:

# Tutorial 
### GCP
**Recording:** [Watch on Loom](https://www.loom.com/share/6d115989ca4848798dafc7fd8ed8f2b9?sid=c2155c02-f3d5-4c87-bfc3-8ef504da48d5)

### Azure
**Recording:** [Watch on Loom](enter URL)

# GCP Screenshots
[URL](gcp/URL.png)

[URL](https://creatinine-value-949334408153.europe-west1.run.app)

[Endpoint](gcp/Live_Endpoint.png)

[Logs](gcp/Logs.png)

[Source Function Code](gcp/Source_Function_Code.png)

[Colab-Abnormal Range](gcp/Abnormal.png)

[Colab-Normal Range](gcp/Normal.png)

# Azure Screenshots
[URL](gcp/URL.png)

[Endpoint](azure/Live_Endpoint.png)

[Logs](azure/Logs.png)

[Source Function Code](azure/Source_Function_Code.png)

[Colab-Abnormal Range](azure/Abnormal.png)

[Colab-Normal Range](azure/Normal.png)

# Comparison Between GCP & Azure 
I found GCP to be easier to deploy a basic HTTP service. It was fast and didn’t ask me a bunch of confusing setup questions. It handles most of the setup for you and gives you a working URL fast. Azure can feel overwhelming at first because of all the extra setup steps and terminology. Azure seems more professional, but also more complicated if you're just trying to learn. I actually got something working on GCP in under 10 minutes, but Azure took longer because I had to figure out what all the parts meant.

## 📚 Citations

> Mayo Foundation for Medical Education and Research. (2025, June 12). *Creatinine test*. Mayo Clinic.  
> https://www.mayoclinic.org/tests-procedures/creatinine-test/about/pac-20384646

> Shamshuddin, S. (2025, September 17). *What Are the Normal Creatinine Level Ranges? A Complete Guide*. Coverfox.  
> https://www.coverfox.com/health-insurance/articles/normal-creatinine-levels/
