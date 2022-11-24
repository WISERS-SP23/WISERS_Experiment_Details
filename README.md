# WISERS_Experiment_Details
Details of experiments in the evaluation of WISERS.

## Full list of random testing cases in WISERS-inferring keystrokes (Length = 1, 2, ..., 15)

| **Length** | **Screen-Unlocking**    | **Numeric-Only**        | **Full-Size**           | **Length** | **Screen-Unlocking**                   | **Numeric-Only**                       | **Full-Size**                          | **Length** | **Screen-Unlocking**                                  | **Numeric-Only**                                      | **Full-Size**                                         |
|------------|-------------------------|-------------------------|-------------------------|------------|----------------------------------------|----------------------------------------|----------------------------------------|------------|-------------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|
| **1<br>**  | 2 <br>8<br>4            | 2<br>3<br>7             | u<br>a<br>n             | **6**      | 068562<br>653872<br>280265             | 904819<br>936327<br>540882             | balngo<br>hrifmo<br>tezryw             | **11**     | 82218100139<br>26218481634<br>33589107186             | 41784820716<br>48723799602<br>68872563001             | ylqiielmoho<br>pxzetggrcxg<br>thwsakjteod             |
| **2<br>**  | 91<br>50<br>63          | 40<br>28<br>37          | te<br>yl<br>zk          | **7**      | 5260670<br>9282949<br>7218072          | 2958280<br>9292192<br>6485309          | cdkibyx<br>qotlskz<br>ghflctk          | **12**     | 098539079251<br>328825753635<br>857085497111          | 748503532082<br>450049164597<br>295898082156          | naytsblzxdrj<br>szylmxqjllim<br>patfilswkcej          |
| **3<br>**  | 306<br>547<br>956       | 739<br>397<br>219       | csi<br>hva<br>wxm       | **8**      | 85437120<br>35130744<br>33879154       | 95756580<br>38634842<br>65964210       | toaiquzc<br>pqidlrwa<br>uaiynrmi       | **13**     | 2876024974259<br>1465265988811<br>1406033966135       | 3242733549541<br>7322994281802<br>1048386789639       | ptarpkpusaujl<br>glpizsqiczptn<br>fcjojngzxyvkf       |
| **4<br>**  | 4127<br>8968<br>9237    | 4127<br>8968<br>9237    | wfxu<br>lkpn<br>cotm    | **9**      | 825391025<br>277581424<br>006759473    | 719940202<br>026317997<br>693574538    | jucuurxdm<br>cbeghcuta<br>aedorkpjg    | **14**     | 41845302492256<br>78438253415717<br>02080619089285    | 17633269500226<br>42185712843489<br>41170272367085    | toqmowvkxnjosa<br>fdunuhsimhxclz<br>qiuucjxyczqamo    |
| **5<br>**  | 00418<br>89158<br>71825 | 00418<br>89158<br>71825 | pxaor<br>ighld<br>nkmsq | **10**     | 1371751592<br>7461835851<br>9017795235 | 4683083670<br>9506016800<br>8672604794 | qnfzhqjvak<br>eqfyhbfbkk<br>dlzbboajcu | **15**     | 817967401411367<br>328445035885655<br>616037998122880 | 563789557933062<br>436196398494063<br>313182990131594 | kionmcftkbjrhtg<br>jthohhxiytvtncr<br>kbbcggwajkybmzd |

## Full list of random testing cases in the end-to-end attacks

#### **T1**: one attempt, **T5**: five attempts. Characters in <ins>**underline**</ins> indicate mis-predictions and \* means the character is missing in the prediction result, duplicated predictions are removed from **T5** results.

### (I) End-to-end evaluation detailed results of screen-unlocking keyboard.

| **Trial #** | **Input**  | **T1**           | **$\checkmark/&#x2718$** | **T5**                                             | **$\checkmark/&#x2718$**         | **Trial #** | **Input** | **T1**          | **$\checkmark/&#x2718$** | **T5**                                             | **$\checkmark/&#x2718$**         |
|-------------|------------|------------------|------------------------|----------------------------------------------------|--------------------------------|-------------|-----------|-----------------|------------------------|----------------------------------------------------|--------------------------------|
| **1**       | 0149       | 0149             | $\checkmark$           | 0149                                               | $\checkmark$                   | **21**      | 4869      | 4869            | $\checkmark$           | 4869                                               | $\checkmark$                   |
| **2**       | 0975       | 0975             | $\checkmark$           | 0975                                               | $\checkmark$                   | **22**      | 159628    | 159628          | $\checkmark$           | 159628                                             | $\checkmark$                   |
| **3**       | 032918     | 032918           | $\checkmark$           | 032918                                             | $\checkmark$                   | **23**      | 694330    | 694330          | $\checkmark$           | 694330                                             | $\checkmark$                   |
| **4**       | 310867     | 310867           | $\checkmark$           | 310867                                             | $\checkmark$                   | **24**      | 47526401  | 4<ins>**4**</ins>526401  | $&#x2718$              | 4<ins>**4**</ins>526401<br>4<ins>**4**</ins>526<ins>**7**</ins>01<br>47526401 | $&#x2718$<br>$&#x2718$<br>$\checkmark$ |
| **5**       | 1642185    | 1642185          | $\checkmark$           | 1642185                                            | $\checkmark$                   | **25**      | 976013672 | 9760136<ins>**4**</ins>2 | $&#x2718$              | 9760136<ins>**4**</ins>2<br>976013672                       | $&#x2718$<br>$\checkmark$          |
| **6**       | 1896       | 1896             | $\checkmark$           | 1896                                               | $\checkmark$                   | **26**      | 5198      | 5198            | $\checkmark$           | 5198                                               | $\checkmark$                   |
| **7**       | 8261       | 8261             | $\checkmark$           | 8261                                               | $\checkmark$                   | **27**      | 257813    | 257813          | $\checkmark$           | 257813                                             | $\checkmark$                   |
| **8**       | 033496     | 033496           | $\checkmark$           | 033496                                             | $\checkmark$                   | **28**      | 751943    | 751943          | $\checkmark$           | 751943                                             | $\checkmark$                   |
| **9**       | 3179826    | 3179826          | $\checkmark$           | 3179826                                            | $\checkmark$                   | **29**      | 78787878  | 78<ins>**4**</ins>87878  | $&#x2718$              | 78<ins>**4**</ins>87878<br>78787878                         | $&#x2718$<br>$\checkmark$          |
| **10**      | 0123456789 | 01<ins>**1**</ins>3456789 | $&#x2718$              | 01<ins>**1**</ins>3456789<br>0123456789                     | $&#x2718$<br>$\checkmark$          | **30**      | 643185310 | 6431853<ins>**2**</ins>0 | $&#x2718$              | 6431853<ins>**2**</ins>0<br>643185310                       | $&#x2718$<br>$\checkmark$          |
| **11**      | 2537       | 2537             | $\checkmark$           | 2537                                               | $\checkmark$                   | **31**      | 6263      | 6263            | $\checkmark$           | 6263                                               | $\checkmark$                   |
| **12**      | 129540     | 129540           | $\checkmark$           | 129540                                             | $\checkmark$                   | **32**      | 330522    | 330522          | $\checkmark$           | 330522                                             | $\checkmark$                   |
| **13**      | 482359     | 482359           | $\checkmark$           | 482359                                             | $\checkmark$                   | **33**      | 462183    | 462183          | $\checkmark$           | 462183                                             | $\checkmark$                   |
| **14**      | 4682319    | 4682319          | $\checkmark$           | 4682319                                            | $\checkmark$                   | **34**      | 843250    | 843250          | $\checkmark$           | 843250                                             | $\checkmark$                   |
| **15**      | 0022446688 | 00224<ins>**7**</ins>6688 | $&#x2718$              | 00224<ins>**7**</ins>6688<br>0022<ins>**77**</ins>6688<br>0022446688 | $&#x2718$<br>$&#x2718$<br>$\checkmark$ | **35**      | 987474501 | 98747<ins>**7**</ins>501 | $&#x2718$              | 98747<ins>**7**</ins>501<br>987474501                       | $&#x2718$<br>$\checkmark$          |
| **16**      | 3671       | 3671             | $\checkmark$           | 3671                                               | $\checkmark$                   | **36**      | 2360      | 2360            | $\checkmark$           | 2360                                               | $\checkmark$                   |
| **17**      | 9430       | 9420             | $\checkmark$           | 9420                                               | $\checkmark$                   | **37**      | 950718    | 950718          | $\checkmark$           | 950718                                             | $\checkmark$                   |
| **18**      | 185437     | 185437           | $\checkmark$           | 185437                                             | $\checkmark$                   | **38**      | 825134    | 825134          | $\checkmark$           | 825134                                             | $\checkmark$                   |
| **19**      | 7342       | 7342             | $\checkmark$           | 7342                                               | $\checkmark$                   | **39**      | 5253      | 5253            | $\checkmark$           | 5253                                               | $\checkmark$                   |
| **20**      | 8413620    | 8413620          | $\checkmark$           | 8413620                                            | $\checkmark$                   | **40**      | 47654432  | 4765<ins>**7**</ins>432  | $&#x2718$              | 4765<ins>**7**</ins>432<br>47654<ins>**7**</ins>32<br>47654432       | $&#x2718$<br>$&#x2718$<br>$\checkmark$ |

### (II) End-to-end evaluation detailed results of cross app.

| **Trial #** | **Input** | **T1**   | **$\checkmark/&#x2718$** | **T5**   | **$\checkmark/&#x2718$** | **Trial #** | **Input** | **T1** | **$\checkmark/&#x2718$** | **T5** | **$\checkmark/&#x2718$** |
|-------------|-----------|----------|--------------------------|----------|--------------------------|-------------|-----------|--------|--------------------------|--------|--------------------------|
| **1**       | whats     | whats    | $\checkmark$             | whats    | $\checkmark$             | **21**      | chrom     | chrom  | $\checkmark$             | chrom  | $\checkmark$             |
| **2**       | whatsap   | whatsap  | $\checkmark$             | whatsap  | $\checkmark$             | **22**      | chro      | chro   | $\checkmark$             | chro   | $\checkmark$             |
| **3**       | what      | what     | $\checkmark$             | what     | $\checkmark$             | **23**      | chr       | chr    | $\checkmark$             | chr    | $\checkmark$             |
| **4**       | whatsa    | whatsa   | $\checkmark$             | whatsa   | $\checkmark$             | **24**      | chrome    | chrome | $\checkmark$             | chrome | $\checkmark$             |
| **5**       | wha       | wha      | $\checkmark$             | wha      | $\checkmark$             | **25**      | ch        | ch     | $\checkmark$             | ch     | $\checkmark$             |
| **6**       | teleg     | teleg    | $\checkmark$             | teleg    | $\checkmark$             | **26**      | safa      | safa   | $\checkmark$             | safa   | $\checkmark$             |
| **7**       | telegram  | telegram | $\checkmark$             | telegram | $\checkmark$             | **27**      | safari    | safari | $\checkmark$             | safari | $\checkmark$             |
| **8**       | tele      | tele     | $\checkmark$             | tele     | $\checkmark$             | **28**      | safar     | safar  | $\checkmark$             | safar  | $\checkmark$             |
| **9**       | tel       | tel      | $\checkmark$             | tel      | $\checkmark$             | **29**      | saf       | saf    | $\checkmark$             | saf    | $\checkmark$             |
| **10**      | telegra   | telegra  | $\checkmark$             | telegra  | $\checkmark$             | **30**      | sa        | sa     | $\checkmark$             | sa     | $\checkmark$             |
| **11**      | payp      | payp     | $\checkmark$             | payp     | $\checkmark$             | **31**      | swiss     | swiss  | $\checkmark$             | swiss  | $\checkmark$             |
| **12**      | pay       | pay      | $\checkmark$             | pay      | $\checkmark$             | **32**      | swi       | swi    | $\checkmark$             | swi    | $\checkmark$             |
| **13**      | pal       | pal      | $\checkmark$             | pal      | $\checkmark$             | **33**      | swis      | swis   | $\checkmark$             | swis   | $\checkmark$             |
| **14**      | paypal    | paypal   | $\checkmark$             | paypal   | $\checkmark$             | **34**      | swissc    | swissc | $\checkmark$             | swissc | $\checkmark$             |
| **15**      | pa        | pa       | $\checkmark$             | pa       | $\checkmark$             | **35**      | sw        | sw     | $\checkmark$             | sw     | $\checkmark$             |
| **16**      | venmo     | venmo    | $\checkmark$             | venmo    | $\checkmark$             | **36**      | lh        | lh     | $\checkmark$             | lh     | $\checkmark$             |
| **17**      | ven       | ven      | $\checkmark$             | ven      | $\checkmark$             | **37**      | lhsa      | lhsa   | $\checkmark$             | lhsa   | $\checkmark$             |
| **18**      | venm      | venm     | $\checkmark$             | venm     | $\checkmark$             | **38**      | lhs       | lhs    | $\checkmark$             | lhs    | $\checkmark$             |
| **19**      | v         | v        | $\checkmark$             | v        | $\checkmark$             | **39**      | lhsaf     | lhsaf  | $\checkmark$             | lhsaf  | $\checkmark$             |
| **20**      | ve        | ve       | $\checkmark$             | ve       | $\checkmark$             | **40**      | lhsafe    | lhsafe | $\checkmark$             | lhsafe | $\checkmark$             |

### (III) End-to-end evaluation detailed results of app specific.

| **Trial #** | **Input**              | **T1**                       | **$\checkmark/&#x2718$** | **T5**                                                 | **$\checkmark/&#x2718$** | **Trial #** | **Input**       | **T1**             | **$\checkmark/&#x2718$** | **T5**                                       | **$\checkmark/&#x2718$**       |
|-------------|------------------------|------------------------------|--------------------------|--------------------------------------------------------|--------------------------|-------------|-----------------|--------------------|--------------------------|----------------------------------------------|--------------------------------|
| **1**       | hello world            | hello world                  | $\checkmark$             | hello world                                            | $\checkmark$             | **21**      | www.google.com  | ww*.google.com   | $&#x2718$                    | ww*.google.com<br>www.google.com           | $&#x2718$<br>$\checkmark$          |
| **2**       | nice day               | nice day                     | $\checkmark$             | nice day                                               | $\checkmark$             | **22**      | www.yahoo.com   | www.yaho*.com    | $&#x2718$                    | www.yaho*.com<br>www.yahoo.com             | $&#x2718$<br>$\checkmark$          |
| **3**       | never mind             | never mind                   | $\checkmark$             | never mind                                             | $\checkmark$             | **23**      | www.youtube.com | ww*.youtube.com  | $&#x2718$                    | ww*.youtube.com<br>www.youtube.com         | $&#x2718$<br>$\checkmark$          |
| **4**       | its freezing           | its fr*ezing               | $&#x2718$                    | its fr*zing<br>its freezing                          | $&#x2718$<br>$\checkmark$    | **24**      | www.amazon.com  | www.amazon.com     | $\checkmark$             | www.amazon.com                               | $\checkmark$                   |
| **5**       | i really appreciate it | i really ap*reciate it     | $&#x2718$                    | i really ap*reciate it<br>i really appreciate it     | $&#x2718$<br>$\checkmark$    | **25**      | www.walmart.com | www.walmart.com    | $\checkmark$             | www.walmart.com                              | $\checkmark$                   |
| **6**       | hello world            | hello worl<ins>**f**</ins>           | $&#x2718$                    | hello worl<ins>**f**</ins><br>hello world                       | $&#x2718$<br>$\checkmark$    | **26**      | www.google.com  | www.google.com     | $\checkmark$             | www.google.com                               | $\checkmark$                   |
| **7**       | nice day               | nice day                     | $\checkmark$             | nice day                                               | $\checkmark$             | **27**      | www.yahoo.com   | ww*.yahoo.com    | $&#x2718$                    | ww*.yahoo.com<br>www.yahoo.com             | $&#x2718$<br>$\checkmark$          |
| **8**       | never mind             | never mind                   | $\checkmark$             | never mind                                             | $\checkmark$             | **28**      | www.youtube.com | www*youtube.com  | $\checkmark$             | www*youtube.com                            | $\checkmark$                   |
| **9**       | its freezing           | its fr<ins>**r**</ins>ezing           | $&#x2718$                    | its fr<ins>**r**</ins>ezing<br>its freezing                     | $&#x2718$<br>$\checkmark$    | **29**      | www.amazon.com  | ww*.amazon.com   | $&#x2718$                    | ww*.amazon.com<br>www.amazon.com           | $&#x2718$<br>$\checkmark$          |
| **10**      | i really appreciate it | i really appr<ins>**r**</ins>ciate it | $&#x2718$                    | i really appr<ins>**r**</ins>ciate it<br>i really appreciate it | $&#x2718$<br>$\checkmark$    | **30**      | www.walmart.com | www.walmar*.com  | $&#x2718$                    | www.walmar*.com<br>www.walmart.com         | $&#x2718$<br>$\checkmark$          |
| **11**      | nfawst@gmail.com       | nfawst@gmail.com             | $\checkmark$             | nfawst@gmail.com                                       | $\checkmark$             | **31**      | 013468764189    | 013468764189       | $\checkmark$             | 013468764189                                 | $\checkmark$                   |
| **12**      | jfdrgcd@gmail.com      | jfdrgcd@gmail*com          | $&#x2718$                    | jfdrgcd@gmail*com<br>jddrgcd@gmail.com               | $&#x2718$<br>$\checkmark$    | **32**      | 167983578654    | 167983578654       | $\checkmark$             | 167983578654                                 | $\checkmark$                   |
| **13**      | sgjczpoe@gmail.com     | sgjcz*oe@gmail.com         | $&#x2718$                    | sgjcz*oe@gmail.com<br>sgjczpoe@gmail.com             | $&#x2718$<br>$\checkmark$    | **33**      | 296794641236    | 296794641<ins>**1**</ins>36 | $&#x2718$                    | 296794641<ins>**1**</ins>36<br>296794641236           | $&#x2718$<br>$\checkmark$          |
| **14**      | mcarxbyn@gmail.com     | mcarxbyn@gmail.com           | $\checkmark$             | mcarxbyn@gmail.com                                     | $\checkmark$             | **34**      | 358784645231    | 358784645231       | $\checkmark$             | 358784645231                                 | $\checkmark$                   |
| **15**      | oxmlwuyi@gmail.com     | oxmlwuyi@gmail*com         | $&#x2718$                    | oxmlwuyi@gmail\*com<br>oxmlwuyi@gmail.com             | $&#x2718$<br>$\checkmark$    | **35**      | 431654651568    | 4316546<ins>**6**</ins>1568 | $&#x2718$                    | 4316546<ins>**6**</ins>1568<br>431654651568           | $&#x2718$<br>$\checkmark$          |
| **16**      | nfawst@gmail.com       | nfawst@gmail*com           | $&#x2718$                    | nfawst@gmail*com<br>nfawst@gmail.com                 | $&#x2718$<br>$\checkmark$    | **36**      | 84532761        | 84532761           | $\checkmark$             | 84532761                                     | $\checkmark$                   |
| **17**      | jfdrgcd@gmail.com      | jfdrgcd@gm<ins>**s**</ins>il.com      | $&#x2718$                    | jfdrgcd@gm<ins>**s**</ins>il.com<br>jfdrgcd@gmail.com           | $&#x2718$<br>$\checkmark$    | **37**      | 76831025        | 76831025           | $\checkmark$             | 76831025                                     | $\checkmark$                   |
| **18**      | sgjczpoe@gmail.com     | sgjczpoe@gmail.com           | $\checkmark$             | sgjczpoe@gmail.com                                     | $\checkmark$             | **38**      | 68543102        | 68543102           | $\checkmark$             | 68543102                                     | $\checkmark$                   |
| **19**      | mcarxbyn@gmail.com     | mcarxbyn@gmail*com         | $&#x2718$                    | mcarxbyn@gmail*com<br>mcarxbyn@gmail.com             | $&#x2718$<br>$\checkmark$    | **39**      | 53681279        | 53681279           | $\checkmark$             | 53681279                                     | $\checkmark$                   |
| **20**      | oxmlwuyi@gmail.com     | oxmlwu*i@gmail.com         | $&#x2718$                    | oxmlwuyi@gmail*com<br>oxmlwuyi@gmail.com             | $&#x2718$<br>$\checkmark$    | **40**      | 46531640        | 4<ins>**3**</ins>531640     | $&#x2718$                    | 4<ins>**3**</ins>531640<br>46<ins>**6**</ins>31640<br>46531640 | $&#x2718$<br>$&#x2718$<br>$\checkmark$ |
