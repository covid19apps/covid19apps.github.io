# <center>Beyond the Virus: A First Look at Coronavirus-themed Mobile Malware </center>
<center>Ren He, Haoyu Wang, Pengcheng Xia, Liu Wang, Yuanchun Li, Lei Wu, Yajin Zhou, Xiapu Luo, Yao Guo, Guoai Xu</center>


# Introduce
As COVID-19 continues to spread across the world, a grow- ing number of malicious campaigns are exploiting the pan- demic. It is reported that COVID-19 is being used in a variety of online malicious activities, including Email scam, ransomware and malicious domains. As the number of the afflicted cases continue to surge, malicious campaigns that use coronavirus as a lure are increasing.

Smartphone, as one of the most popular ways to keep track of the most up-to-date status of the pandemic and receive notifications, has always been the major target of the mali- cious campaigns. As the coronavirus outbreak increased in severity across the world, people tend to use mobile apps that can provide information on actions for avoiding infection, updates regarding COVID-19, as well as medical services. Thus, malicious developers take advantage of this opportu- nity to lure mobile users to download and install malicious apps. Indeed, some news reports, show that COVID-19 related malicious apps have been observed, and thousands of mobile users have been affected in another way (by the virtual Virus) in this pandemic. For example, the malicious website (coronavirusapp.site) prompts users to download a malicious Android App that will give them access to a coronavirus map tracker that appears to provide tracking and statistical information about COVID-19. How- ever, the app is indeed a ransomware that locks users’ screen, which requests $100 in Bitcoin to unlock the phone.

However, besides a few media reports, the coronavirus- themed mobile malware has not been well studied. Our community lacks of the comprehensive understanding of the landscape of the coronavirus-themed mobile malware, and no accessible dataset could be used by our researchers to boost COVID-19 related cybersecurity studies.

<b>This Work</b>. To this end, this paper presents the first measurement study of COVID-19 related Android malware. We first make efforts to create a daily growing COVID-19 re- lated mobile app dataset, by collecting samples from a number of sources, including app markets (both Google Play and alternative app markets), a well-known app repository (i.e., Koodous) and the COVID-19 related domains (apps downloaded or connected to these domains). By the time of paper writing, we have curated a dataset of 2,016 COVID-19 themed apps, and 277 of them are considered to be malicious. 

![trend](https://github.com/covid19apps/covid19apps.github.io/raw/master/trend.jpg)

The number of COVID-19 related apps and malware over the time (from January to May 2020).


# Dataset
In our dataset, we collect 2,016 COVID-19 themed apps and 277 of them are them are considered to be malicious. To boost the research on coronavirus-themed cybersecurity threats, We have released a daily growing dataset to the research community.

In this page, we show all the COVID-19 themed apps information, including apk file hashes, released date, package name, AV-Rank, etc. For more details, please click [COVID-19 themed apps Information](https://covid19apps.github.io/covid19apps) or [download](https://github.com/covid19apps/covid19apps.github.io/blob/master/covid19apps.xlsx) the file.<br/>

We are happy to share our COIVD19 themed dataset (APK file). However, in order to prevent any misuse, we kindly ask you to send us a mail to <covid19apps@outlook.com> stating your identity and research scope. We will then send you the APK file samples.


If your papers or articles use our dataset, please use the following bibtex reference to cite our paper:

        @misc{he2020virus,
            title={Beyond the Virus: A First Look at Coronavirus-themed Mobile Malware},
            author={Ren He and Haoyu Wang and Pengcheng Xia and Liu Wang and Yuanchun Li and Lei Wu and Yajin Zhou and Xiapu Luo and Yao Guo and Guoai Xu},
            year={2020},
            eprint={2005.14619},
            archivePrefix={arXiv},
            primaryClass={cs.CR}
        }
