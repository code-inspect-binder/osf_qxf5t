# Executable Environment for OSF Project [qxf5t](https://osf.io/qxf5t/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Cultures under stress: A cross-national meta-analysis of cortisol responses to the Trier Social Stress Test and their association with internalizing mental disorders and anxiety-based values

**Project Description:**
> Acute cortisol changes are physiological indicators (i.e., biomarkers) of psychosocial stress that have been repeatedly assessed using standardized laboratory protocols like the Trier Social Stress Test (TSST). Despite of this methodological standardization, however, cortisol stress responses vary considerably across different studies. Based on multilevel meta-analyses of 237 TSST studies (n = 8487 individuals), we demonstrate that ~25% of this variability is actually attributable to systematic differences between countries. Particularly North American and European studies show a remarkable effect disparity (d = 0.45 vs. d = 0.73).
In accordance with this finding, the increased prevalence of internalizing mental disorders (e.g. major depression or post-traumatic stress disorder) in English-speaking countries as reported by the WHO World Mental Health Surveys, a larger inequality of family incomes, larger population growth, larger expenses for health and the military, lower tax rates, and a cultural orientation towards anxiety-related values are accompanied by substantially decreased cortisol stress responses. Intriguingly, the size of these effects is comparable to the most important moderators of cortisol changes known to date, that is, male sex and higher age.
Proceeding from these results, we argue that the cortisol stress response may reflect the persistent threats in the sociocultural environment an individual is accustomed too. Highly competitive cultures emphasize the individuals’ responsibility for socioeconomic prosperity, but simultaneously increase the collective population stress and thus lower sustainable ontogeny and resilience towards unexpected environmental adversity.

**Original OSF Page:** [https://osf.io/qxf5t/](https://osf.io/qxf5t/)

---

**Important Note:** The contents of the `qxf5t_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_qxf5t/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_qxf5t/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `qxf5t_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-qxf5t:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-qxf5t
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
