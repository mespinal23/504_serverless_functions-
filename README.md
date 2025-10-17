# 504_serverless_functions-
Implementation HTTP Serverless Function

# Lab Rules
A creatinine test is a measure of how well the kidneys are doing their job of filtering waste from the blood.
Creatinine is a chemical compound left over from energy-making processes in muscles. Healthy kidneys filter creatinine out of the blood. Creatinine exits the body as a waste product in urine.
A measurement of creatinine in your blood or urine helps your healthcare professional find out how well your kidneys are working.

**Serum creatinine** is reported as milligrams of creatinine to a deciliter of blood (mg/dL). Or it's reported as micromoles of creatinine to a liter of blood (µmol/L). 

### The typical range for serum creatinine is:

**For adult men, 0.74 to 1.35 mg/dL (65.4 to 119.3 µmol/L)**

**For adult women, 0.59 to 1.04 mg/dL (52.2 to 91.9 µmol/L)**

<img src="https://cms-img.coverfox.com/Normal-Creatinine-Level-Ranges.jpeg" alt="Creatinine Level Chart" width="400"/>

## 📚 Citation

> Mayo Foundation for Medical Education and Research. (2025, June 12). *Creatinine test*. Mayo Clinic.  
> https://www.mayoclinic.org/tests-procedures/creatinine-test/about/pac-20384646

> Shamshuddin, S. (2025, September 17). *What Are the Normal Creatinine Level Ranges? A Complete Guide*. Coverfox.  
> https://www.coverfox.com/health-insurance/articles/normal-creatinine-levels/

# Cloud Environment
- Google Cloud Platform
  - Region: Belgium
- Microsoft Azure
  - Region: West US 3

# Deployment commands or steps you executed

# Screenshots showing functionality that have your custom URLs, along with outputs

# Public endpoint URLs (+ notes on auth: unauthenticated vs key‑based)

- Example `requests` invocations that **work as shown** in your video
  
# Comparison Between GCP & Azure 
I found GCP to be easier to deploy a basic HTTP service. It was fast and didn’t ask me a bunch of confusing setup questions. It handles most of the setup for you and gives you a working URL fast. Azure can feel overwhelming at first because of all the extra setup steps and terminology. Azure seems more professional, but also more complicated if you're just trying to learn. I actually got something working on GCP in under 10 minutes, but Azure took longer because I had to figure out what all the parts meant.
  
### 3) Deliverables  
    - **Publicly accessible endpoint URLs** for each deployed function (paste into the README).  
    - **Recording (Zoom or Loom)** showing:
        - A quick code tour.
        - At least one **live GET/POST request** using python `requests` in either a notebook or script file, and the **JSON response**.
        - Where logs/monitoring appear in each cloud.

### Recording Requirements (2–4 minutes)
- Brief intro (name, which two clouds you chose).
- Show your repository and where the cloud‑specific code lives.
- Show the live endpoint(s) and execute a POST request with two examples (one normal, one abnormal).
- Show where to find **logs** or **monitoring** in each cloud’s portal.
- Mention any gotchas (permissions, runtime version, cold starts).

Upload the recording and place a **shareable link** in your README.


