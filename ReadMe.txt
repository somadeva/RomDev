v0.3. An improved version of my earlier TECkit map to dynamically convert UTF8 Romanized Sanskrit and Prakrit to Devanagari in XeLaTeX. This version fixes:

—Roman capitals are converted.

—Prakrit medial Vowels are handled gracefully without the need for {} (except, of course, for ambiguous diphthongs such as ai vs. a{}i).

—Added a common quotemark U+2019 > avagraha.

—Better handling of conjuncts by avoiding unnecessary joiners (Thanks to J.D. Smith for this improvement which meant searchable DN!).
                         
—Support for Prakrit. You can use diaereses (gaa = gaä) and breves (only initial short e and o for now, e.g. ĕttha etc. ) and tildes to mark prosodically short nasalisations (e.g. tāĩ vs. tāiṃ or tāïṃ). 
                                                                                          
Outstanding is support for Vedic accents.