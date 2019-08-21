# Filters

```sql
SELECT codes.CLID, codes.ID, codelist_def.MNU, codes.DESCRP FROM codes JOIN codelist_def ON codes.CLID = codelist_def.ID;
```

|CLID|ID|MNU|DESCRP|
|-|-|-|-|
1| 2| ACCTYP| Total: Accommodation type
1| 3| ACCTYP| Unshared dwelling
1| 4| ACCTYP| Whole house or bungalow
1| 5| ACCTYP| Detached
1| 6| ACCTYP| Semi-detached
1| 7| ACCTYP| Terraced (including end-terrace)
1| 8| ACCTYP| Flat| maisonette or apartment
1| 9| ACCTYP| Purpose-built block of flats or tenement
1| 10| ACCTYP| Part of a converted or shared house (including bed-sits)
1| 11| ACCTYP| In commercial building
1| 12| ACCTYP| Caravan or other mobile or temporary structure
1| 13| ACCTYP| Shared dwelling
2| 14| ADLFA| Total: Adult lifestage (alternative adult definition)
2| 15| ADLFA| Total
2| 16| ADLFA| No dependent children in household
2| 17| ADLFA| Dependent children in household
2| 18| ADLFA| Dependent child in household
2| 19| ADLFA| Youngest aged 0 to 4
2| 20| ADLFA| Youngest aged 5 to 10
2| 21| ADLFA| Youngest aged 11 to 15
2| 22| ADLFA| Youngest aged 16 to 18
2| 23| ADLFA| One person household
2| 24| ADLFA| Two or more person household
2| 25| ADLFA| No dependent children
3| 26| AGE| Total: Age
3| 27| AGE| Age 0 to 4
3| 28| AGE| Age 5 to 7
3| 29| AGE| Age 8 to 9
3| 30| AGE| Age 10 to 14
3| 31| AGE| Age 15
3| 32| AGE| Age 16 to 17
3| 33| AGE| Age 18 to 19
3| 34| AGE| Age 20 to 24
3| 35| AGE| Age 25 to 29
3| 36| AGE| Age 30 to 44
3| 37| AGE| Age 45 to 59
3| 38| AGE| Age 60 to 64
3| 39| AGE| Age 65 to 74
3| 40| AGE| Age 75 to 84
3| 41| AGE| Age 85 to 89
3| 42| AGE| Age 90 and over
3| 43| AGE| Mean age
3| 44| AGE| Median age
3| 45| AGE| Age 16 and over
3| 46| AGE| Age 16 to 74
3| 47| AGE| Age 3 and over
3| 48| AGE| Age 3 to 15
3| 49| AGE| Age 16 to 64
3| 50| AGE| Age 65 and over
3| 51| AGE| Age 18 to 74
3| 52| AGE| Age 16 to 24
3| 53| AGE| Age 50 to 74
3| 54| AGE| Age under 1
3| 55| AGE| Age 1
3| 56| AGE| Age 2
3| 57| AGE| Age 3
3| 58| AGE| Age 4
3| 59| AGE| Age 5
3| 60| AGE| Age 6
3| 61| AGE| Age 7
3| 62| AGE| Age 8
3| 63| AGE| Age 9
3| 64| AGE| Age 10
3| 65| AGE| Age 11
3| 66| AGE| Age 12
3| 67| AGE| Age 13
3| 68| AGE| Age 14
3| 69| AGE| Age 16
3| 70| AGE| Age 17
3| 71| AGE| Age 18
3| 72| AGE| Age 19
3| 73| AGE| Age 20
3| 74| AGE| Age 21
3| 75| AGE| Age 22
3| 76| AGE| Age 23
3| 77| AGE| Age 24
3| 78| AGE| Age 25
3| 79| AGE| Age 26
3| 80| AGE| Age 27
3| 81| AGE| Age 28
3| 82| AGE| Age 29
3| 83| AGE| Age 30
3| 84| AGE| Age 31
3| 85| AGE| Age 32
3| 86| AGE| Age 33
3| 87| AGE| Age 34
3| 88| AGE| Age 35
3| 89| AGE| Age 36
3| 90| AGE| Age 37
3| 91| AGE| Age 38
3| 92| AGE| Age 39
3| 93| AGE| Age 40
3| 94| AGE| Age 41
3| 95| AGE| Age 42
3| 96| AGE| Age 43
3| 97| AGE| Age 44
3| 98| AGE| Age 45
3| 99| AGE| Age 46
3| 100| AGE| Age 47
3| 101| AGE| Age 48
3| 102| AGE| Age 49
3| 103| AGE| Age 50
3| 104| AGE| Age 51
3| 105| AGE| Age 52
3| 106| AGE| Age 53
3| 107| AGE| Age 54
3| 108| AGE| Age 55
3| 109| AGE| Age 56
3| 110| AGE| Age 57
3| 111| AGE| Age 58
3| 112| AGE| Age 59
3| 113| AGE| Age 60
3| 114| AGE| Age 61
3| 115| AGE| Age 62
3| 116| AGE| Age 63
3| 117| AGE| Age 64
3| 118| AGE| Age 65
3| 119| AGE| Age 66
3| 120| AGE| Age 67
3| 121| AGE| Age 68
3| 122| AGE| Age 69
3| 123| AGE| Age 70
3| 124| AGE| Age 71
3| 125| AGE| Age 72
3| 126| AGE| Age 73
3| 127| AGE| Age 74
3| 128| AGE| Age 75
3| 129| AGE| Age 76
3| 130| AGE| Age 77
3| 131| AGE| Age 78
3| 132| AGE| Age 79
3| 133| AGE| Age 80
3| 134| AGE| Age 81
3| 135| AGE| Age 82
3| 136| AGE| Age 83
3| 137| AGE| Age 84
3| 138| AGE| Age 85
3| 139| AGE| Age 86
3| 140| AGE| Age 87
3| 141| AGE| Age 88
3| 142| AGE| Age 89
3| 143| AGE| Age 90
3| 144| AGE| Age 91
3| 145| AGE| Age 92
3| 146| AGE| Age 93
3| 147| AGE| Age 94
3| 148| AGE| Age 95
3| 149| AGE| Age 96
3| 150| AGE| Age 97
3| 151| AGE| Age 98
3| 152| AGE| Age 99
3| 153| AGE| Age 100 and over
3| 154| AGE| Age 4 and over
3| 155| AGE| Age 25 to 34
3| 156| AGE| Age 35 to 54
3| 157| AGE| Age 55 to 64
3| 158| AGE| Age 75 and over
3| 159| AGE| Age 18 to 64
3| 160| AGE| Age under 65
4| 161| AGEAUK| Total: Age upon arrival in the UK
4| 162| AGEAUK| Born in the UK
4| 163| AGEAUK| Age 0 to 4
4| 164| AGEAUK| Age 5 to 7
4| 165| AGEAUK| Age 8 to 9
4| 166| AGEAUK| Age 10 to 14
4| 167| AGEAUK| Age 15
4| 168| AGEAUK| Age 16 to 17
4| 169| AGEAUK| Age 18 to 19
4| 170| AGEAUK| Age 20 to 24
4| 171| AGEAUK| Age 25 to 29
4| 172| AGEAUK| Age 30 to 44
4| 173| AGEAUK| Age 45 to 59
4| 174| AGEAUK| Age 60 to 64
4| 175| AGEAUK| Age 65 to 74
4| 176| AGEAUK| Age 75 to 84
4| 177| AGEAUK| Age 85 to 89
4| 178| AGEAUK| Age 90 and over
5| 179| AGECHD| All ages
5| 180| AGECHD| Age 0 to 4
6| 181| AGEHRP| Total
6| 182| AGEHRP| Age under 35
6| 183| AGEHRP| Age 35 to 54
6| 184| AGEHRP| Age 55 to 64
6| 185| AGEHRP| Age 65 and over
6| 186| AGEHRP| Age under 65
90| 187| AGEFRP| Age 16 to 64
7| 188| AGESST| Age 16 to 17
7| 189| AGESST| Age 18 and over
9| 190| ASGHRP| Total: Approximated social grade of Household Reference Person
9| 191| ASGHRP| Approximated social grade AB
9| 192| ASGHRP| Approximated social grade C1
9| 193| ASGHRP| Approximated social grade C2
9| 194| ASGHRP| Approximated social grade DE
10| 195| CARVAN| Total: Car or van availability
10| 196| CARVAN| No cars or vans in household
10| 197| CARVAN| 1 car or van in household
10| 198| CARVAN| 2 cars or vans in household
10| 199| CARVAN| 3 cars or vans in household
10| 200| CARVAN| 4 or more cars or vans in household
11| 201| CLSHHD| Total: Classification of household deprivation
11| 202| CLSHHD| Household is not deprived in any dimension
11| 203| CLSHHD| Household is deprived in 1 dimension
11| 204| CLSHHD| Household is deprived in 2 dimensions
11| 205| CLSHHD| Household is deprived in 3 dimensions
11| 206| CLSHHD| Household is deprived in 4 dimensions
13| 207| COMEMT| All communal establishments
13| 208| COMEMT| Total: Communal establishment management and type
13| 209| COMEMT| Medical and care establishment
13| 210| COMEMT| NHS
13| 211| COMEMT| General hospital
13| 212| COMEMT| Mental health hospital/unit (including secure units)
13| 213| COMEMT| Other hospital
13| 214| COMEMT| Local Authority
13| 215| COMEMT| Children's home (including secure units)
13| 216| COMEMT| Care home or other home
13| 217| COMEMT| Registered Social Landlord/Housing Association
13| 218| COMEMT| Other
13| 219| COMEMT| Care home with nursing
13| 220| COMEMT| Care home without nursing
13| 221| COMEMT| Children's home (including secure units)
13| 222| COMEMT| Other establishments
13| 223| COMEMT| Establishment not stated
13| 224| COMEMT| Care home with nursing
13| 225| COMEMT| Care home without nursing
13| 226| COMEMT| Other home
13| 227| COMEMT| Home or hostel
13| 228| COMEMT| Sheltered housing only
13| 229| COMEMT| Mental health hospital/unit (including secure units)
13| 230| COMEMT| Other hospital
13| 231| COMEMT| Other establishment
13| 232| COMEMT| Other establishment
13| 233| COMEMT| Defence
13| 234| COMEMT| Prison service
13| 235| COMEMT| Approved premises (probation/bail hostel)
13| 236| COMEMT| Detention centres and other detention
13| 237| COMEMT| Education
13| 238| COMEMT| Hotel
13| 239| COMEMT| Guest house| B&B or youth hostel
13| 240| COMEMT| Hostel or temporary shelter for the homeless
13| 241| COMEMT| Holiday accommodation (for example holiday parks)
13| 242| COMEMT| Other travel or temporary accommodation
13| 243| COMEMT| Religious
13| 244| COMEMT| Staff/worker accommodation only
13| 245| COMEMT| Other
12| 246| COB| Total: Country of birth
12| 247| COB| Europe
12| 248| COB| United Kingdom
12| 249| COB| England
12| 250| COB| Northern Ireland
12| 251| COB| Scotland
12| 252| COB| Wales
12| 253| COB| United Kingdom (not otherwise specified)
12| 254| COB| Ireland
12| 255| COB| Other Europe
12| 256| COB| EU countries
12| 257| COB| Member countries in March 2001
12| 258| COB| Accession countries April 2001 to March 2011
12| 259| COB| Other countries
12| 260| COB| Great Britain (not otherwise specified)
12| 261| COB| Guernsey
12| 262| COB| Jersey
12| 263| COB| Channel Islands (not otherwise specified)
12| 264| COB| Isle of Man
12| 265| COB| Austria
12| 266| COB| Belgium
12| 267| COB| Denmark
12| 268| COB| Finland
12| 269| COB| France
12| 270| COB| Germany
12| 271| COB| Gibraltar
12| 272| COB| Greece
12| 273| COB| Italy
12| 274| COB| Luxembourg
12| 275| COB| Netherlands
12| 276| COB| Portugal (including Madeira and the Azores)
12| 277| COB| Spain (including Canary Islands)
12| 278| COB| Sweden
12| 279| COB| Other member countries in March 2001
12| 280| COB| Bulgaria
12| 281| COB| Cyprus (European Union)
12| 282| COB| Czech Republic
12| 283| COB| Estonia
12| 284| COB| Hungary
12| 285| COB| Latvia
12| 286| COB| Lithuania
12| 287| COB| Malta
12| 288| COB| Poland
12| 289| COB| Romania
12| 290| COB| Slovakia
12| 291| COB| Slovenia
12| 292| COB| Czechoslovakia (not otherwise specified)
12| 293| COB| Rest of Europe
12| 294| COB| Albania
12| 295| COB| Armenia
12| 296| COB| Azerbaijan
12| 297| COB| Belarus
12| 298| COB| Bosnia and Herzegovina
12| 299| COB| Croatia
12| 300| COB| Cyprus (non-European Union)
12| 301| COB| Georgia
12| 302| COB| Iceland
12| 303| COB| Kosovo
12| 304| COB| Macedonia
12| 305| COB| Moldova
12| 306| COB| Montenegro
12| 307| COB| Norway
12| 308| COB| Russia
12| 309| COB| Serbia
12| 310| COB| Switzerland
12| 311| COB| Turkey
12| 312| COB| Ukraine
12| 313| COB| Union of Soviet Socialist Republics (not otherwise specified)
12| 314| COB| Yugoslavia (not otherwise specified)
12| 315| COB| Other rest of Europe
12| 316| COB| Africa
12| 317| COB| North Africa
12| 318| COB| Algeria
12| 319| COB| Egypt
12| 320| COB| Libya
12| 321| COB| Morocco
12| 322| COB| Sudan
12| 323| COB| Tunisia
12| 324| COB| Other North Africa
12| 325| COB| Central and Western Africa
12| 326| COB| Angola
12| 327| COB| Cameroon
12| 328| COB| Cape Verde
12| 329| COB| Congo
12| 330| COB| Congo (Democratic Republic)
12| 331| COB| The Gambia
12| 332| COB| Ghana
12| 333| COB| Guinea
12| 334| COB| Guinea-Bissau
12| 335| COB| Ivory Coast
12| 336| COB| Liberia
12| 337| COB| Nigeria
12| 338| COB| Senegal
12| 339| COB| Sierra Leone
12| 340| COB| St. Helena
12| 341| COB| Togo
12| 342| COB| Other Central and Western Africa
12| 343| COB| South and Eastern Africa
12| 344| COB| Botswana
12| 345| COB| Burundi
12| 346| COB| Eritrea
12| 347| COB| Ethiopia
12| 348| COB| Kenya
12| 349| COB| Madagascar
12| 350| COB| Malawi
12| 351| COB| Mauritius
12| 352| COB| Mozambique
12| 353| COB| Namibia
12| 354| COB| Rwanda
12| 355| COB| Seychelles
12| 356| COB| Somalia
12| 357| COB| South Africa
12| 358| COB| Swaziland
12| 359| COB| Tanzania
12| 360| COB| Uganda
12| 361| COB| Zambia
12| 362| COB| Zimbabwe
12| 363| COB| Other South and Eastern Africa
12| 364| COB| Africa (not otherwise specified)
12| 365| COB| Middle East and Asia
12| 366| COB| Middle East
12| 367| COB| Bahrain
12| 368| COB| Iran
12| 369| COB| Iraq
12| 370| COB| Israel
12| 371| COB| Jordan
12| 372| COB| Kuwait
12| 373| COB| Lebanon
12| 374| COB| Occupied Palestinian Territories
12| 375| COB| Oman
12| 376| COB| Qatar
12| 377| COB| Saudi Arabia
12| 378| COB| Syria
12| 379| COB| United Arab Emirates
12| 380| COB| Yemen
12| 381| COB| Middle East (not otherwise specified)
12| 382| COB| Eastern Asia
12| 383| COB| China
12| 384| COB| Hong Kong (Special Administrative Region of China)
12| 385| COB| Japan
12| 386| COB| Korea (North)
12| 387| COB| Korea (South)
12| 388| COB| Macao (Special Administrative Region of China)
12| 389| COB| Mongolia
12| 390| COB| Taiwan
12| 391| COB| Southern Asia
12| 392| COB| Afghanistan
12| 393| COB| Bangladesh
12| 394| COB| India
12| 395| COB| Nepal
12| 396| COB| Pakistan
12| 397| COB| Sri Lanka
12| 398| COB| Other Southern Asia
12| 399| COB| South-East Asia
12| 400| COB| Brunei
12| 401| COB| Burma
12| 402| COB| Cambodia
12| 403| COB| Indonesia
12| 404| COB| Malaysia
12| 405| COB| Philippines
12| 406| COB| Singapore
12| 407| COB| Thailand
12| 408| COB| Vietnam
12| 409| COB| Other South-East Asia
12| 410| COB| Central Asia
12| 411| COB| Kazakhstan
12| 412| COB| Kyrgyzstan
12| 413| COB| Uzbekistan
12| 414| COB| Other Central Asia
12| 415| COB| The Americas and the Caribbean
12| 416| COB| North America
12| 417| COB| Bermuda
12| 418| COB| Canada
12| 419| COB| United States
12| 420| COB| Other North America
12| 421| COB| Central America
12| 422| COB| Belize
12| 423| COB| Mexico
12| 424| COB| Other Central America
12| 425| COB| South America
12| 426| COB| Argentina
12| 427| COB| Bolivia
12| 428| COB| Brazil
12| 429| COB| Chile
12| 430| COB| Colombia
12| 431| COB| Ecuador
12| 432| COB| Guyana
12| 433| COB| Peru
12| 434| COB| Uruguay
12| 435| COB| Venezuela
12| 436| COB| Other South America
12| 437| COB| The Caribbean
12| 438| COB| Antigua and Barbuda
12| 439| COB| The Bahamas
12| 440| COB| Barbados
12| 441| COB| Cuba
12| 442| COB| Dominica
12| 443| COB| Dominican Republic
12| 444| COB| Grenada
12| 445| COB| Jamaica
12| 446| COB| Montserrat
12| 447| COB| St. Kitts and Nevis
12| 448| COB| St. Lucia
12| 449| COB| St. Vincent and the Grenadines
12| 450| COB| Trinidad and Tobago
12| 451| COB| Other Caribbean
12| 452| COB| Antarctica and Oceania
12| 453| COB| Antarctica
12| 454| COB| Australasia
12| 455| COB| Australia
12| 456| COB| New Zealand
12| 457| COB| Other Australasia
12| 458| COB| Oceania
12| 459| COB| Fiji
12| 460| COB| Papua New Guinea
12| 461| COB| Other Oceania
12| 462| COB| Other
76| 463| COBDET| Total: Country of birth (detailed)
76| 464| COBDET| Europe
76| 465| COBDET| United Kingdom
76| 466| COBDET| England
76| 467| COBDET| Northern Ireland
76| 468| COBDET| Scotland
76| 469| COBDET| Wales
76| 470| COBDET| Great Britain (not otherwise specified)
76| 471| COBDET| United Kingdom (not otherwise specified)
76| 472| COBDET| Guernsey
76| 473| COBDET| Jersey
76| 474| COBDET| Channel Islands (not otherwise specified)
76| 475| COBDET| Isle of Man
76| 476| COBDET| Ireland
76| 477| COBDET| Other Europe
76| 478| COBDET| EU Countries
76| 479| COBDET| Member countries in March 2001
76| 480| COBDET| France
76| 481| COBDET| Germany
76| 482| COBDET| Italy
76| 483| COBDET| Portugal
76| 484| COBDET| Spain (including Canary Islands)
76| 485| COBDET| Other member countries in March 2001
76| 486| COBDET| Accession countries April 2001 to March 2011
76| 487| COBDET| Lithuania
76| 488| COBDET| Poland
76| 489| COBDET| Romania
76| 490| COBDET| Other EU accession countries
76| 491| COBDET| Rest of Europe
76| 492| COBDET| Turkey
76| 493| COBDET| Other Europe
76| 494| COBDET| Africa
76| 495| COBDET| North Africa
76| 496| COBDET| Central and Western Africa
76| 497| COBDET| Ghana
76| 498| COBDET| Nigeria
76| 499| COBDET| Other Central and Western Africa
76| 500| COBDET| South and Eastern Africa
76| 501| COBDET| Kenya
76| 502| COBDET| Somalia
76| 503| COBDET| South Africa
76| 504| COBDET| Zimbabwe
76| 505| COBDET| Other South and Eastern Africa
76| 506| COBDET| Africa (not otherwise specified)
76| 507| COBDET| Middle East and Asia
76| 508| COBDET| Middle East
76| 509| COBDET| Iran
76| 510| COBDET| Other Middle East
76| 511| COBDET| Eastern Asia
76| 512| COBDET| China
76| 513| COBDET| Hong Kong (Special Administrative Region of China)
76| 514| COBDET| Other Eastern Asia
76| 515| COBDET| Southern Asia
76| 516| COBDET| Bangladesh
76| 517| COBDET| India
76| 518| COBDET| Pakistan
76| 519| COBDET| Sri Lanka
76| 520| COBDET| Other Southern Asia
76| 521| COBDET| South-East Asia
76| 522| COBDET| Philippines
76| 523| COBDET| Other South-East Asia
76| 524| COBDET| Central Asia
76| 525| COBDET| The Americas and the Caribbean
76| 526| COBDET| North America
76| 527| COBDET| United States
76| 528| COBDET| Other North America
76| 529| COBDET| Central America
76| 530| COBDET| South America
76| 531| COBDET| The Caribbean
76| 532| COBDET| Jamaica
76| 533| COBDET| Other Caribbean
76| 534| COBDET| Antarctica and Oceania
76| 535| COBDET| Antarctica
76| 536| COBDET| Australasia
76| 537| COBDET| Australia
76| 538| COBDET| Other Australasia
76| 539| COBDET| Other Oceania
76| 540| COBDET| Other
15| 541| DEPCHD| With dependent children
15| 542| DEPCHD| No dependent children
15| 543| DEPCHD| Dependent children in household
16| 544| DPCHDF| All categories: Dependent children in family
16| 545| DPCHDF| No dependent children in family
16| 546| DPCHDF| One dependent child in family
16| 547| DPCHDF| Aged 0 to 4
16| 548| DPCHDF| Aged 5 to 11
16| 549| DPCHDF| Aged 12 to 18
16| 550| DPCHDF| Two dependent children in family
16| 551| DPCHDF| Youngest aged 0 to 4
16| 552| DPCHDF| Youngest aged 5 to 11
16| 553| DPCHDF| Youngest aged 12 to 18
16| 554| DPCHDF| Three or more dependent children in family
16| 555| DPCHDF| Youngest aged 0 to 4
16| 556| DPCHDF| Youngest aged 5 to 11
16| 557| DPCHDF| Youngest aged 12 to 18
16| 558| DPCHDF| Total dependent children
17| 559| DWLTYP| Total: Dwellings
17| 560| DWLTYP| Unshared dwelling
17| 561| DWLTYP| Shared dwelling
17| 562| DWLTYP| Two household spaces
17| 563| DWLTYP| Three or more household spaces
18| 564| ECOACT| Total: Economic activity
18| 565| ECOACT| Economically active
18| 566| ECOACT| Employed
18| 567| ECOACT| Part-time
18| 568| ECOACT| Full-time
18| 569| ECOACT| Unemployed
18| 570| ECOACT| Full-time students
18| 571| ECOACT| In employment
18| 572| ECOACT| Unemployed
18| 573| ECOACT| Economically inactive
18| 574| ECOACT| Full-time students
18| 575| ECOACT| Employee
18| 576| ECOACT| Part-time
18| 577| ECOACT| Full-time
18| 578| ECOACT| Self-employed
18| 579| ECOACT| Full-time student
18| 580| ECOACT| Retired
18| 581| ECOACT| Student (including full-time students)
18| 582| ECOACT| Looking after home or family
18| 583| ECOACT| Long-term sick or disabled
18| 584| ECOACT| Other
18| 585| ECOACT| Unemployed
18| 586| ECOACT| Never worked
18| 587| ECOACT| Long-term unemployed
18| 588| ECOACT| In employment the week before the census
18| 589| ECOACT| Self-employed with employees
18| 590| ECOACT| Part-time
18| 591| ECOACT| Full-time
18| 592| ECOACT| Self-employed without employees
18| 593| ECOACT| Part-time
18| 594| ECOACT| Full-time
19| 595| ECPHRP| Total: Economic activity of Household Reference Persons
19| 596| ECPHRP| Economically active
19| 597| ECPHRP| Employee
19| 598| ECPHRP| Part-time
19| 599| ECPHRP| Full-time
19| 600| ECPHRP| Self-employed with employees
19| 601| ECPHRP| Part-time
19| 602| ECPHRP| Full-time
19| 603| ECPHRP| Self-employed without employees
19| 604| ECPHRP| Part-time
19| 605| ECPHRP| Full-time
19| 606| ECPHRP| Unemployed
19| 607| ECPHRP| Full-time student
19| 608| ECPHRP| Economically inactive
19| 609| ECPHRP| Retired
19| 610| ECPHRP| Student (including full-time students)
19| 611| ECPHRP| Looking after home or family
19| 612| ECPHRP| Long-term sick or disabled
19| 613| ECPHRP| Other
21| 614| ENGHHL| Total: English as a household language
21| 615| ENGHHL| All people aged 16 and over in household have English as a main language (English or Welsh in Wales)
21| 616| ENGHHL| At least one but not all people aged 16 and over in household have English as a main language (English or Welsh in Wales)
21| 617| ENGHHL| No people aged 16 and over in household but at least one person aged 3 to 15 has English as a main language (English or Welsh in Wales)
21| 618| ENGHHL| No people in household have English as a main language (English or Welsh in Wales)
22| 619| ETHGRP| Total: Ethnic group
22| 620| ETHGRP| White
22| 621| ETHGRP| English/Welsh/Scottish/Northern Irish/British
22| 622| ETHGRP| Irish
22| 623| ETHGRP| Gypsy or Irish Traveller
22| 624| ETHGRP| Other White
22| 625| ETHGRP| Mixed/multiple ethnic group
22| 626| ETHGRP| White and Black Caribbean
22| 627| ETHGRP| White and Black African
22| 628| ETHGRP| White and Asian
22| 629| ETHGRP| Other Mixed
22| 630| ETHGRP| Asian/Asian British
22| 631| ETHGRP| Indian
22| 632| ETHGRP| Pakistani
22| 633| ETHGRP| Bangladeshi
22| 634| ETHGRP| Chinese
22| 635| ETHGRP| Other Asian
22| 636| ETHGRP| Black/African/Caribbean/Black British
22| 637| ETHGRP| African
22| 638| ETHGRP| Caribbean
22| 639| ETHGRP| Other Black
22| 640| ETHGRP| Other ethnic group
22| 641| ETHGRP| Arab
22| 642| ETHGRP| Any other ethnic group
20| 643| EGRPDT| Total: Ethnic group (detailed)
20| 644| EGRPDT| White
20| 645| EGRPDT| English/Welsh/Scottish/Northern Irish/British
20| 646| EGRPDT| Irish
20| 647| EGRPDT| Gypsy or Irish Traveller
20| 648| EGRPDT| Afghan
20| 649| EGRPDT| Albanian
20| 650| EGRPDT| Anglo Indian
20| 651| EGRPDT| Argentinian
20| 652| EGRPDT| Australian/New Zealander
20| 653| EGRPDT| Baltic States
20| 654| EGRPDT| Bosnian
20| 655| EGRPDT| Brazilian
20| 656| EGRPDT| British Asian
20| 657| EGRPDT| Burmese
20| 658| EGRPDT| Chilean
20| 659| EGRPDT| Colombian
20| 660| EGRPDT| Commonwealth of (Russian) Independent States
20| 661| EGRPDT| Croatian
20| 662| EGRPDT| Cuban
20| 663| EGRPDT| Cypriot (part not stated)
20| 664| EGRPDT| Ecuadorian
20| 665| EGRPDT| European Mixed
20| 666| EGRPDT| Filipino
20| 667| EGRPDT| Greek
20| 668| EGRPDT| Greek Cypriot
20| 669| EGRPDT| Iranian
20| 670| EGRPDT| Israeli
20| 671| EGRPDT| Italian
20| 672| EGRPDT| Japanese
20| 673| EGRPDT| Kashmiri
20| 674| EGRPDT| Kosovan
20| 675| EGRPDT| Kurdish
20| 676| EGRPDT| Latin/South/Central American
20| 677| EGRPDT| Malaysian
20| 678| EGRPDT| Mexican
20| 679| EGRPDT| Moroccan
20| 680| EGRPDT| Multi-ethnic islands
20| 681| EGRPDT| Nepalese (includes Gurkha)
20| 682| EGRPDT| Nigerian
20| 683| EGRPDT| North African
20| 684| EGRPDT| North American
20| 685| EGRPDT| Other Eastern European
20| 686| EGRPDT| Other Middle East
20| 687| EGRPDT| Other Western European
20| 688| EGRPDT| Peruvian
20| 689| EGRPDT| Polish
20| 690| EGRPDT| Polynesia/Micronesia/Melanesia
20| 691| EGRPDT| Serbian
20| 692| EGRPDT| Somali
20| 693| EGRPDT| Somalilander
20| 694| EGRPDT| Sri Lankan
20| 695| EGRPDT| Tamil
20| 696| EGRPDT| Thai
20| 697| EGRPDT| Turkish
20| 698| EGRPDT| Turkish Cypriot
20| 699| EGRPDT| Venezuelan
20| 700| EGRPDT| Vietnamese
20| 701| EGRPDT| White African
20| 702| EGRPDT| White Caribbean
20| 703| EGRPDT| Any other ethnic group
20| 704| EGRPDT| Mixed/multiple ethnic group
20| 705| EGRPDT| White and Black Caribbean
20| 706| EGRPDT| White and Black African
20| 707| EGRPDT| White and Asian
20| 708| EGRPDT| Afghan
20| 709| EGRPDT| African/Arab
20| 710| EGRPDT| Albanian
20| 711| EGRPDT| Anglo Indian
20| 712| EGRPDT| Australian/New Zealander
20| 713| EGRPDT| Baltic States
20| 714| EGRPDT| Black and Asian
20| 715| EGRPDT| Black and Chinese
20| 716| EGRPDT| Black and White
20| 717| EGRPDT| Black British
20| 718| EGRPDT| Black European
20| 719| EGRPDT| Black/African American
20| 720| EGRPDT| Brazilian
20| 721| EGRPDT| British Asian
20| 722| EGRPDT| Burmese
20| 723| EGRPDT| Caribbean Asian
20| 724| EGRPDT| Chilean
20| 725| EGRPDT| Chinese and White
20| 726| EGRPDT| Colombian
20| 727| EGRPDT| Commonwealth of (Russian) Independent States
20| 728| EGRPDT| Cuban
20| 729| EGRPDT| Cypriot (part not stated)
20| 730| EGRPDT| East African Asian
20| 731| EGRPDT| Ecuadorian
20| 732| EGRPDT| European Mixed
20| 733| EGRPDT| Filipino
20| 734| EGRPDT| Greek
20| 735| EGRPDT| Greek Cypriot
20| 736| EGRPDT| Indonesian
20| 737| EGRPDT| Iranian
20| 738| EGRPDT| Israeli
20| 739| EGRPDT| Italian
20| 740| EGRPDT| Japanese
20| 741| EGRPDT| Kashmiri
20| 742| EGRPDT| Korean
20| 743| EGRPDT| Kosovan
20| 744| EGRPDT| Kurdish
20| 745| EGRPDT| Latin/South/Central American
20| 746| EGRPDT| Malaysian
20| 747| EGRPDT| Mexican
20| 748| EGRPDT| Moroccan
20| 749| EGRPDT| Multi-ethnic islands
20| 750| EGRPDT| Nepalese (includes Gurkha)
20| 751| EGRPDT| Nigerian
20| 752| EGRPDT| North African
20| 753| EGRPDT| North American
20| 754| EGRPDT| Other Eastern European
20| 755| EGRPDT| Other Middle East
20| 756| EGRPDT| Other Western European
20| 757| EGRPDT| Peruvian
20| 758| EGRPDT| Polish
20| 759| EGRPDT| Polynesia/Micronesia/Melanesia
20| 760| EGRPDT| Somali
20| 761| EGRPDT| South Asian and Chinese
20| 762| EGRPDT| Sri Lankan
20| 763| EGRPDT| Tamil
20| 764| EGRPDT| Thai
20| 765| EGRPDT| Turkish
20| 766| EGRPDT| Turkish Cypriot
20| 767| EGRPDT| Venezuelan
20| 768| EGRPDT| Vietnamese
20| 769| EGRPDT| White African
20| 770| EGRPDT| White and Arab
20| 771| EGRPDT| White and East Asian
20| 772| EGRPDT| White and North African or Middle Eastern
20| 773| EGRPDT| White and South Asian
20| 774| EGRPDT| White Caribbean
20| 775| EGRPDT| Any other ethnic group
20| 776| EGRPDT| Asian/Asian British
20| 777| EGRPDT| Indian or British Indian
20| 778| EGRPDT| Pakistani or British Pakistani
20| 779| EGRPDT| Bangladeshi or British Bangladeshi
20| 780| EGRPDT| Chinese
20| 781| EGRPDT| Afghan
20| 782| EGRPDT| Anglo Indian
20| 783| EGRPDT| British Asian
20| 784| EGRPDT| Burmese
20| 785| EGRPDT| Cambodia
20| 786| EGRPDT| Caribbean Asian
20| 787| EGRPDT| Commonwealth of (Russian) Independent States
20| 788| EGRPDT| East African Asian
20| 789| EGRPDT| European Mixed
20| 790| EGRPDT| Filipino
20| 791| EGRPDT| Indonesian
20| 792| EGRPDT| Iranian
20| 793| EGRPDT| Italian
20| 794| EGRPDT| Japanese
20| 795| EGRPDT| Kashmiri
20| 796| EGRPDT| Korean
20| 797| EGRPDT| Kurdish
20| 798| EGRPDT| Latin/South/Central American
20| 799| EGRPDT| Malaysian
20| 800| EGRPDT| Multi-ethnic islands
20| 801| EGRPDT| Nepalese (includes Gurkha)
20| 802| EGRPDT| North American
20| 803| EGRPDT| Other Eastern European
20| 804| EGRPDT| Other Middle East
20| 805| EGRPDT| Other Western European
20| 806| EGRPDT| Polynesia/Micronesia/Melanesia
20| 807| EGRPDT| Punjabi
20| 808| EGRPDT| Sinhalese
20| 809| EGRPDT| Somali
20| 810| EGRPDT| Sri Lankan
20| 811| EGRPDT| Taiwanese
20| 812| EGRPDT| Tamil
20| 813| EGRPDT| Thai
20| 814| EGRPDT| Turkish
20| 815| EGRPDT| Turkish Cypriot
20| 816| EGRPDT| Vietnamese
20| 817| EGRPDT| Any other ethnic group
20| 818| EGRPDT| Black/African/Caribbean/Black British
20| 819| EGRPDT| African
20| 820| EGRPDT| Caribbean
20| 821| EGRPDT| Afghan
20| 822| EGRPDT| African/Arab
20| 823| EGRPDT| Black British
20| 824| EGRPDT| Black European
20| 825| EGRPDT| Black/African American
20| 826| EGRPDT| Brazilian
20| 827| EGRPDT| Caribbean Asian
20| 828| EGRPDT| Colombian
20| 829| EGRPDT| Cuban
20| 830| EGRPDT| European Mixed
20| 831| EGRPDT| Filipino
20| 832| EGRPDT| Italian
20| 833| EGRPDT| Latin/South/Central American
20| 834| EGRPDT| Moroccan
20| 835| EGRPDT| Multi-ethnic islands
20| 836| EGRPDT| Nigerian
20| 837| EGRPDT| North African
20| 838| EGRPDT| North American
20| 839| EGRPDT| Other Western European
20| 840| EGRPDT| Polynesia/Micronesia/Melanesia
20| 841| EGRPDT| Somali
20| 842| EGRPDT| Somalilander
20| 843| EGRPDT| Sri Lankan
20| 844| EGRPDT| Any other ethnic group
20| 845| EGRPDT| Other ethnic group
20| 846| EGRPDT| Arab
20| 847| EGRPDT| Afghan
20| 848| EGRPDT| African/Arab
20| 849| EGRPDT| Albanian
20| 850| EGRPDT| Anglo-Indian
20| 851| EGRPDT| Australian/New Zealander
20| 852| EGRPDT| Baltic States
20| 853| EGRPDT| Bosnian
20| 854| EGRPDT| Brazilian
20| 855| EGRPDT| Burmese
20| 856| EGRPDT| Caribbean Asian
20| 857| EGRPDT| Chilean
20| 858| EGRPDT| Colombian
20| 859| EGRPDT| Commonwealth of (Russian) Independent States
20| 860| EGRPDT| Cypriot (part not stated)
20| 861| EGRPDT| Ecuadorian
20| 862| EGRPDT| European Mixed
20| 863| EGRPDT| Filipino
20| 864| EGRPDT| Greek
20| 865| EGRPDT| Greek Cypriot
20| 866| EGRPDT| Indonesian
20| 867| EGRPDT| Iranian
20| 868| EGRPDT| Israeli
20| 869| EGRPDT| Italian
20| 870| EGRPDT| Japanese
20| 871| EGRPDT| Kashmiri
20| 872| EGRPDT| Korean
20| 873| EGRPDT| Kosovan
20| 874| EGRPDT| Kurdish
20| 875| EGRPDT| Latin/South/Central American
20| 876| EGRPDT| Malaysian
20| 877| EGRPDT| Mexican
20| 878| EGRPDT| Moroccan
20| 879| EGRPDT| Multi-ethnic islands
20| 880| EGRPDT| Nepalese (includes Gurkha)
20| 881| EGRPDT| North African
20| 882| EGRPDT| North American
20| 883| EGRPDT| Other Eastern European
20| 884| EGRPDT| Other Middle East
20| 885| EGRPDT| Other Western European
20| 886| EGRPDT| Peruvian
20| 887| EGRPDT| Polish
20| 888| EGRPDT| Polynesia/Micronesia/Melanesia
20| 889| EGRPDT| Punjabi
20| 890| EGRPDT| Somali
20| 891| EGRPDT| Somalilander
20| 892| EGRPDT| Sri Lankan
20| 893| EGRPDT| Tamil
20| 894| EGRPDT| Thai
20| 895| EGRPDT| Turkish
20| 896| EGRPDT| Turkish Cypriot
20| 897| EGRPDT| Vietnamese
20| 898| EGRPDT| Any other ethnic group
23| 899| ETHWRI| Total: Ethnic group (write-in responses)
23| 900| ETHWRI| English/Welsh/Scottish/Northern Irish/British
23| 901| ETHWRI| Irish
23| 902| ETHWRI| Gypsy or Irish Traveller
23| 903| ETHWRI| Other White
23| 904| ETHWRI| White and Black Caribbean
23| 905| ETHWRI| White and Black African
23| 906| ETHWRI| White and Asian
23| 907| ETHWRI| Other mixed
23| 908| ETHWRI| Indian or British Indian
23| 909| ETHWRI| Pakistani or British Pakistani
23| 910| ETHWRI| Bangladeshi| British Bangladeshi
23| 911| ETHWRI| Chinese
23| 912| ETHWRI| Other Asian
23| 913| ETHWRI| African
23| 914| ETHWRI| Caribbean
23| 915| ETHWRI| Other Black
23| 916| ETHWRI| Arab
23| 917| ETHWRI| Any other ethnic group
23| 918| ETHWRI| Afghan
23| 919| ETHWRI| African/Arab
23| 920| ETHWRI| Albanian
23| 921| ETHWRI| Anglo Indian
23| 922| ETHWRI| Argentinian
23| 923| ETHWRI| Australian/New Zealander
23| 924| ETHWRI| Baltic States
23| 925| ETHWRI| Black and Asian
23| 926| ETHWRI| Black and Chinese
23| 927| ETHWRI| Black and White
23| 928| ETHWRI| Black British
23| 929| ETHWRI| Black European
23| 930| ETHWRI| Black/African American
23| 931| ETHWRI| Bosnian
23| 932| ETHWRI| Brazilian
23| 933| ETHWRI| British Asian
23| 934| ETHWRI| Burmese
23| 935| ETHWRI| Cambodia
23| 936| ETHWRI| Caribbean Asian
23| 937| ETHWRI| Chilean
23| 938| ETHWRI| Chinese and White
23| 939| ETHWRI| Colombian
23| 940| ETHWRI| Commonwealth of (Russian) Independent States
23| 941| ETHWRI| Croatian
23| 942| ETHWRI| Cuban
23| 943| ETHWRI| Cypriot
23| 944| ETHWRI| East African Asian
23| 945| ETHWRI| Ecuadorian
23| 946| ETHWRI| European Mixed
23| 947| ETHWRI| Filipino
23| 948| ETHWRI| Greek
23| 949| ETHWRI| Greek Cypriot
23| 950| ETHWRI| Indonesian
23| 951| ETHWRI| Iranian
23| 952| ETHWRI| Israeli
23| 953| ETHWRI| Italian
23| 954| ETHWRI| Japanese
23| 955| ETHWRI| Kashmiri
23| 956| ETHWRI| Korean
23| 957| ETHWRI| Kosovan
23| 958| ETHWRI| Kurdish
23| 959| ETHWRI| Latin/South/Central American
23| 960| ETHWRI| Malaysian
23| 961| ETHWRI| Mexican
23| 962| ETHWRI| Moroccan
23| 963| ETHWRI| Multi-ethnic islands
23| 964| ETHWRI| Nepalese (includes Gurkha)
23| 965| ETHWRI| Nigerian
23| 966| ETHWRI| North African
23| 967| ETHWRI| North American
23| 968| ETHWRI| Other Eastern European
23| 969| ETHWRI| Other Middle East
23| 970| ETHWRI| Other Western European
23| 971| ETHWRI| Peruvian
23| 972| ETHWRI| Polish
23| 973| ETHWRI| Polynesia/Micronesia/Melanesia
23| 974| ETHWRI| Punjabi
23| 975| ETHWRI| Serbian
23| 976| ETHWRI| Sinhalese
23| 977| ETHWRI| Somali
23| 978| ETHWRI| Somalilander
23| 979| ETHWRI| South Asian and Chinese
23| 980| ETHWRI| Sri Lankan
23| 981| ETHWRI| Taiwanese
23| 982| ETHWRI| Tamil
23| 983| ETHWRI| Thai
23| 984| ETHWRI| Turkish
23| 985| ETHWRI| Turkish Cypriot
23| 986| ETHWRI| Venezuelan
23| 987| ETHWRI| Vietnamese
23| 988| ETHWRI| White African
23| 989| ETHWRI| White and Arab
23| 990| ETHWRI| White and East Asian
23| 991| ETHWRI| White and North African or Middle Eastern
23| 992| ETHWRI| White and South Asian
23| 993| ETHWRI| White Caribbean
24| 995| FAMSTA| Lone-parent
26| 996| GENHEA| Very good health
26| 997| GENHEA| Good health
26| 998| GENHEA| Fair health
26| 999| GENHEA| Bad health
26| 1000| GENHEA| Very bad health
26| 1001| GENHEA| Total: General health
33| 1002| HIQUAL| Total: Highest level of qualification
33| 1003| HIQUAL| No qualifications
33| 1004| HIQUAL| Level 1 qualifications
33| 1005| HIQUAL| Level 2 qualifications
33| 1006| HIQUAL| Apprenticeship
33| 1007| HIQUAL| Level 3 qualifications
33| 1008| HIQUAL| Level 4 qualifications and above
33| 1009| HIQUAL| Other qualifications
34| 1010| HRSWRK| All categories: Hours worked
34| 1011| HRSWRK| Part-time
34| 1012| HRSWRK| 15 hours or less worked
34| 1013| HRSWRK| 16 to 30 hours worked
34| 1014| HRSWRK| Full-time
34| 1015| HRSWRK| 31 to 48 hours worked
34| 1016| HRSWRK| 49 or more hours worked
28| 1017| HHDCOM| Total: Household composition
28| 1018| HHDCOM| One person household
28| 1019| HHDCOM| Aged 65 and over
28| 1020| HHDCOM| Aged 0 to 64
28| 1021| HHDCOM| One family only
28| 1022| HHDCOM| All aged 65 and over
28| 1023| HHDCOM| Married or same-sex civil partnership couple
28| 1024| HHDCOM| No children
28| 1025| HHDCOM| Dependent children
28| 1026| HHDCOM| All children non-dependent
28| 1027| HHDCOM| Cohabiting couple
28| 1028| HHDCOM| No children
28| 1029| HHDCOM| Dependent children
28| 1030| HHDCOM| All children non-dependent
28| 1031| HHDCOM| Lone parent
28| 1032| HHDCOM| Dependent children
28| 1033| HHDCOM| All children non-dependent
28| 1034| HHDCOM| Other household types
28| 1035| HHDCOM| With dependent children
28| 1036| HHDCOM| All full-time students
28| 1037| HHDCOM| All aged 65 and over
28| 1038| HHDCOM| Other
28| 1039| HHDCOM| Married couple
28| 1040| HHDCOM| No children
28| 1041| HHDCOM| One dependent child
28| 1042| HHDCOM| Two or more dependent children
28| 1043| HHDCOM| All children non-dependent
28| 1044| HHDCOM| Same-sex civil partnership couple
28| 1045| HHDCOM| No children
28| 1046| HHDCOM| One dependent child
28| 1047| HHDCOM| Two or more dependent children
28| 1048| HHDCOM| All children non-dependent
28| 1049| HHDCOM| One dependent child
28| 1050| HHDCOM| Two or more dependent children
28| 1051| HHDCOM| One dependent child
28| 1052| HHDCOM| Two or more dependent children
28| 1053| HHDCOM| With one dependent child
28| 1054| HHDCOM| With two or more dependent children
27| 1055| GHCMCAD| Total: Household composition (alternative child and adult definitions)
27| 1056| GHCMCAD| One person household
27| 1057| GHCMCAD| One person aged 65 and over
27| 1058| GHCMCAD| One person aged under 65
27| 1059| GHCMCAD| Other households
27| 1060| GHCMCAD| No adults or one adult and one or more children
27| 1061| GHCMCAD| One adult aged 16 to 64 and one aged 65 and over and no children or two adults aged 65 and over and no children
27| 1062| GHCMCAD| Two adults and one or two children
27| 1063| GHCMCAD| Two adults aged 16 to 64 and no children
27| 1064| GHCMCAD| Two adults and three or more children
27| 1065| GHCMCAD| Three or more adults and one or more children
27| 1066| GHCMCAD| Three or more adults and no children
29| 1067| HHLIFS| Total: Household lifestage
29| 1068| HHLIFS| Total
29| 1069| HHLIFS| One person household
29| 1070| HHLIFS| Two or more person household
29| 1071| HHLIFS| No dependent children
29| 1072| HHLIFS| With dependent children
30| 1073| HHSIZE| Average household size (persons per household)
30| 1074| HHSIZE| Total: Household size
30| 1075| HHSIZE| 1 person in household
30| 1076| HHSIZE| 2 people in household
30| 1077| HHSIZE| 3 people in household
30| 1078| HHSIZE| 4 people in household
30| 1079| HHSIZE| 5 people in household
30| 1080| HHSIZE| 6 people in household
30| 1081| HHSIZE| 7 people in household
30| 1082| HHSIZE| 8 or more people in household
31| 1083| HHSPAC| Total: Household spaces
31| 1084| HHSPAC| Household spaces with at least one usual resident
31| 1085| HHSPAC| Household spaces with no usual residents
105| 1086| HHSPTY| Whole house or bungalow
105| 1087| HHSPTY| Detached
105| 1088| HHSPTY| Semi-detached
105| 1089| HHSPTY| Terraced (including end-terrace)
105| 1090| HHSPTY| Flat| maisonette or apartment
105| 1091| HHSPTY| Purpose-built block of flats or tenement
105| 1092| HHSPTY| Part of a converted or shared house (including bed-sits)
105| 1093| HHSPTY| In a commercial building
105| 1094| HHSPTY| Caravan or other mobile or temporary structure
32| 1095| HHTYPE| Total: Household type
32| 1096| HHTYPE| One person household
32| 1097| HHTYPE| Married couple household
32| 1098| HHTYPE| With dependent children
32| 1099| HHTYPE| No dependent children
32| 1100| HHTYPE| Same-sex civil partnership couple household
32| 1101| HHTYPE| With dependent children
32| 1102| HHTYPE| No dependent children
32| 1103| HHTYPE| Cohabiting couple household
32| 1104| HHTYPE| With dependent children
32| 1105| HHTYPE| No dependent children
32| 1106| HHTYPE| Lone-parent household
32| 1107| HHTYPE| With dependent children
32| 1108| HHTYPE| No dependent children
32| 1109| HHTYPE| Multi-person household
32| 1110| HHTYPE| All full-time students
32| 1111| HHTYPE| Other
35| 1112| INDUST| Total: Industry
35| 1113| INDUST| A Agriculture| forestry and fishing
35| 1114| INDUST| B Mining and quarrying
35| 1115| INDUST| C Manufacturing
35| 1116| INDUST| D Electricity| gas| steam and air conditioning supply
35| 1118| INDUST| F Construction
35| 1119| INDUST| G Wholesale and retail trade; repair of motor vehicles and motor cycles
35| 1120| INDUST| H Transport and storage
35| 1121| INDUST| I Accommodation and food service activities
35| 1122| INDUST| J Information and communication
35| 1123| INDUST| K Financial and insurance activities
35| 1124| INDUST| L Real estate activities
35| 1125| INDUST| M Professional| scientific and technical activities
35| 1126| INDUST| N Administrative and support service activities
35| 1127| INDUST| O Public administration and defence; compulsory social security
35| 1128| INDUST| P Education
35| 1129| INDUST| Q Human health and social work activities
35| 1130| INDUST| R| S| T| U Other
35| 1131| INDUST| C10-12 Manufacturing
35| 1132| INDUST| C10-12 Manufacturing: Food| beverages and tobacco
35| 1133| INDUST| C13-15 Manufacturing
35| 1134| INDUST| C13-15 Manufacturing: Textiles| wearing apparel and leather and related products
35| 1135| INDUST| C16|17 Manufacturing
35| 1136| INDUST| C16|17 Manufacturing: Wood| paper and paper products
35| 1137| INDUST| C19-22 Manufacturing
35| 1138| INDUST| C19-22 Manufacturing: Chemicals| chemical products| rubber and plastic
35| 1139| INDUST| C23-25 Manufacturing
35| 1140| INDUST| C23-25 Manufacturing: Low tech
35| 1141| INDUST| C26-30 Manufacturing
35| 1142| INDUST| C26-30 Manufacturing: High tech
35| 1143| INDUST| C18| 31| 32 Manufacturing
35| 1144| INDUST| C18| 31| 32 Manufacturing: Other
35| 1145| INDUST| E Water supply| sewerage| waste management and remediation activities
35| 1146| INDUST| R|S Arts| entertainment and recreation; other service activities
35| 1147| INDUST| T Activities of households as employers; undifferentiated goods - and services - producing activities of households for own use
35| 1148| INDUST| U Activities of extraterritorial organisations and bodies
38| 1149| LRESUK| Total: Length of residence in the UK
38| 1150| LRESUK| Born in the UK
38| 1151| LRESUK| Resident in UK
38| 1152| LRESUK| Less than 2 years
38| 1153| LRESUK| 2 years or more but less than 5 years
38| 1154| LRESUK| 5 years or more but less than 10 years
38| 1155| LRESUK| 10 years or more
36| 1156| LICARG| Total: Living arrangements
36| 1157| LICARG| Living in a couple
36| 1158| LICARG| Married or in a registered same-sex civil partnership
36| 1159| LICARG| Cohabiting
36| 1160| LICARG| Not living in a couple
36| 1161| LICARG| Single (never married or never registered a same-sex civil partnership)
36| 1162| LICARG| Married or in a registered same-sex civil partnership
36| 1163| LICARG| Separated (but still legally married or still legally in a same-sex civil partnership)
36| 1164| LICARG| Divorced or formerly in a same-sex civil partnership which is now legally dissolved
36| 1165| LICARG| Widowed or surviving partner from a same-sex civil partnership
36| 1166| LICARG| Married
36| 1167| LICARG| Cohabiting (opposite-sex)
36| 1168| LICARG| In a registered same-sex civil partnership or cohabiting (same-sex)
37| 1170| LLHPDI| Total: Long-term health problem or disability
37| 1171| LLHPDI| Day-to-day activities limited a lot
37| 1172| LLHPDI| Day-to-day activities limited a little
37| 1173| LLHPDI| Day-to-day activities not limited
42| 1174| MLANDET| Total: Main language (detailed)
42| 1175| MLANDET| English (English or Welsh if in Wales)
42| 1176| MLANDET| Welsh/Cymraeg (in England only)
42| 1177| MLANDET| Other UK language
42| 1178| MLANDET| Irish Gaelic
42| 1179| MLANDET| Scottish Gaelic
42| 1180| MLANDET| Manx Gaelic
42| 1181| MLANDET| Gaelic (not otherwise specified)
42| 1182| MLANDET| Cornish
42| 1183| MLANDET| Scots
42| 1184| MLANDET| Gypsy/Traveller languages
42| 1185| MLANDET| French
42| 1186| MLANDET| Portuguese
42| 1187| MLANDET| Spanish
42| 1188| MLANDET| Other European language (EU)
42| 1189| MLANDET| Italian
42| 1190| MLANDET| German
42| 1191| MLANDET| Polish
42| 1192| MLANDET| Slovak
42| 1193| MLANDET| Czech
42| 1194| MLANDET| Romanian
42| 1195| MLANDET| Lithuanian
42| 1196| MLANDET| Latvian
42| 1197| MLANDET| Hungarian
42| 1198| MLANDET| Bulgarian
42| 1199| MLANDET| Greek
42| 1200| MLANDET| Dutch
42| 1201| MLANDET| Swedish
42| 1202| MLANDET| Danish
42| 1203| MLANDET| Finnish
42| 1204| MLANDET| Estonian
42| 1205| MLANDET| Slovenian
42| 1206| MLANDET| Maltese
42| 1207| MLANDET| Any other European language (EU)
42| 1208| MLANDET| Other European language (non-EU)
42| 1209| MLANDET| Albanian
42| 1210| MLANDET| Serbian/Croatian/Bosnian
42| 1211| MLANDET| Ukrainian
42| 1212| MLANDET| Any other Eastern European language (non-EU)
42| 1213| MLANDET| Northern European language (non-EU)
42| 1214| MLANDET| Other European language (non-national)
42| 1215| MLANDET| Any Romani language
42| 1216| MLANDET| Yiddish
42| 1217| MLANDET| Russian
42| 1218| MLANDET| Turkish
42| 1219| MLANDET| Arabic
42| 1220| MLANDET| West/Central Asian language
42| 1221| MLANDET| Hebrew
42| 1222| MLANDET| Kurdish
42| 1223| MLANDET| Persian/Farsi
42| 1224| MLANDET| Pashto
42| 1225| MLANDET| Any other West/Central Asian language
42| 1226| MLANDET| South Asian language
42| 1227| MLANDET| Urdu
42| 1228| MLANDET| Hindi
42| 1229| MLANDET| Panjabi
42| 1230| MLANDET| Pakistani Pahari (including Mirpuri and Potwari)
42| 1231| MLANDET| Bengali (including Sylheti and Chatgaya)
42| 1232| MLANDET| Gujarati
42| 1233| MLANDET| Marathi
42| 1234| MLANDET| Telugu
42| 1235| MLANDET| Tamil
42| 1236| MLANDET| Malayalam
42| 1237| MLANDET| Sinhala
42| 1238| MLANDET| Nepalese
42| 1239| MLANDET| South Asian language (all other)
42| 1240| MLANDET| East Asian language
42| 1241| MLANDET| Mandarin Chinese
42| 1242| MLANDET| Cantonese Chinese
42| 1243| MLANDET| Any other Chinese
42| 1244| MLANDET| Japanese
42| 1245| MLANDET| Korean
42| 1246| MLANDET| Vietnamese
42| 1247| MLANDET| Thai
42| 1248| MLANDET| Malay
42| 1249| MLANDET| Tagalog/Filipino
42| 1250| MLANDET| Any other East Asian language
42| 1251| MLANDET| Any Oceanic/Australian language
42| 1252| MLANDET| Any North/South American language
42| 1253| MLANDET| Caribbean Creole
42| 1254| MLANDET| Caribbean Creole (English-based)
42| 1255| MLANDET| Any other Caribbean Creole
42| 1256| MLANDET| African language
42| 1257| MLANDET| Amharic
42| 1258| MLANDET| Tigrinya
42| 1259| MLANDET| Somali
42| 1260| MLANDET| Krio
42| 1261| MLANDET| Akan
42| 1262| MLANDET| Yoruba
42| 1263| MLANDET| Igbo
42| 1264| MLANDET| Swahili/Kiswahili
42| 1265| MLANDET| Luganda
42| 1266| MLANDET| Lingala
42| 1267| MLANDET| Shona
42| 1268| MLANDET| Afrikaans
42| 1269| MLANDET| Any other Nigerian language
42| 1270| MLANDET| Any other West African language
42| 1271| MLANDET| Any other African language
42| 1272| MLANDET| Other language
42| 1273| MLANDET| Any other spoken language
42| 1274| MLANDET| Sign language
42| 1275| MLANDET| British sign language
42| 1276| MLANDET| Any other sign language
42| 1277| MLANDET| Any sign communication system
39| 1278| MACPST| Total: Marital and civil partnership status
39| 1279| MACPST| Single (never married or never registered a same-sex civil partnership)
39| 1280| MACPST| Married
39| 1281| MACPST| In a registered same-sex civil partnership
39| 1282| MACPST| Separated (but still legally married or still legally in a same-sex civil partnership)
39| 1283| MACPST| Divorced or formerly in a same-sex civil partnership which is now legally dissolved
39| 1284| MACPST| Widowed or surviving partner from a same-sex civil partnership
43| 1285| MTTWRK| Total: Method of travel to work
43| 1286| MTTWRK| Work mainly at or from home
43| 1287| MTTWRK| Underground| metro| light rail| tram
43| 1288| MTTWRK| Train
43| 1289| MTTWRK| Bus| minibus or coach
43| 1290| MTTWRK| Taxi
43| 1291| MTTWRK| Motorcycle| scooter or moped
43| 1292| MTTWRK| Driving a car or van
43| 1293| MTTWRK| Passenger in a car or van
43| 1294| MTTWRK| Bicycle
43| 1295| MTTWRK| On foot
43| 1296| MTTWRK| Other method of travel to work
43| 1297| MTTWRK| Not in employment
41| 1298| METHGR| Total: Multiple ethnic groups
41| 1299| METHGR| One person household
41| 1300| METHGR| All household members have the same ethnic group
41| 1301| METHGR| Different ethnic groups between the generations only
41| 1302| METHGR| Different ethnic groups within partnerships (whether or not different ethnic groups between generations)
41| 1303| METHGR| Any other combination of multiple ethnic groups
45| 1304| NATIDE| Total: National identity English
45| 1305| NATIDE| National identity English
45| 1306| NATIDE| English only identity
45| 1307| NATIDE| English and British only identity
45| 1308| NATIDE| Other English combined background identity
45| 1309| NATIDE| No English identity
45| 1310| NATIDE| Total: National identity Welsh
45| 1311| NATIDE| National identity Welsh
45| 1312| NATIDE| Welsh only identity
45| 1313| NATIDE| Welsh and British only identity
45| 1314| NATIDE| Other Welsh combined background identity
45| 1315| NATIDE| No Welsh identity
45| 1316| NATIDE| Total: National identity Scottish
45| 1317| NATIDE| National identity Scottish
45| 1318| NATIDE| Scottish only identity
45| 1319| NATIDE| Scottish and British only identity
45| 1320| NATIDE| Other Scottish combined background identity
45| 1321| NATIDE| No Scottish identity
45| 1322| NATIDE| Total: National identity Northern Irish
45| 1323| NATIDE| National identity Northern Irish
45| 1324| NATIDE| Northern Irish only identity
45| 1325| NATIDE| Northern Irish and British only identity
45| 1326| NATIDE| Other Northern Irish combined background identity
45| 1327| NATIDE| No Northern Irish identity
45| 1328| NATIDE| Total: National identity British
45| 1329| NATIDE| National identity British
45| 1330| NATIDE| British only identity
45| 1331| NATIDE| British and any other identity
45| 1332| NATIDE| No British identity
45| 1333| NATIDE| Total: National identity Cornish
45| 1334| NATIDE| National identity Cornish
45| 1335| NATIDE| Cornish only identity
45| 1336| NATIDE| Cornish and British only identity
45| 1337| NATIDE| Cornish and at least one of English/Welsh/Scottish/Northern Irish identities (with or without British)
45| 1338| NATIDE| No Cornish identity
45| 1339| NATIDE| Total: National identity Irish
45| 1340| NATIDE| National identity Irish
45| 1341| NATIDE| Irish only identity
45| 1342| NATIDE| Irish and British only identity
45| 1343| NATIDE| Irish and Northern Irish only identity
45| 1344| NATIDE| Irish| Northern Irish and British only identity
45| 1345| NATIDE| Irish and at least one of English/Welsh/Scottish identities (with or without British)
45| 1346| NATIDE| Irish| Northern Irish and at least one of English/Welsh/Scottish identities (with or without British)
45| 1347| NATIDE| No Irish identity
45| 1348| NATIDE| Total: National identity Other
45| 1349| NATIDE| National identity Other
45| 1350| NATIDE| Other identities only
45| 1351| NATIDE| Other identities and at least one of English/Welsh/Scottish/Northern Irish/British only
45| 1352| NATIDE| At least one of English/Welsh/Scottish/Northern Irish/British identities only
45| 1353| NATIDE| Total: National identity
45| 1354| NATIDE| UK identities
45| 1355| NATIDE| British/English/Northern Irish/Scottish/Welsh/Cornish identities only
45| 1356| NATIDE| British only identity
45| 1357| NATIDE| English only identity
45| 1358| NATIDE| English and British only identity
45| 1359| NATIDE| Welsh only identity
45| 1360| NATIDE| Welsh and British only identity
45| 1361| NATIDE| Scottish only identity
45| 1362| NATIDE| Scottish and British only identity
45| 1363| NATIDE| Northern Irish only identity
45| 1364| NATIDE| Northern Irish and British only identity
45| 1365| NATIDE| Cornish only identity
45| 1366| NATIDE| Cornish and British only identity
45| 1367| NATIDE| Any other combination of British/English/Northern Irish/Scottish/Welsh/Cornish identities
45| 1368| NATIDE| Other identity and at least one of British/English/Northern Irish/Scottish/Welsh identities
45| 1369| NATIDE| Other identities only
45| 1370| NATIDE| Guernsey Islander
45| 1371| NATIDE| Jersey Islander
45| 1372| NATIDE| Isle of Man (Manx)
45| 1373| NATIDE| Channel Islander (not otherwise specified)
45| 1374| NATIDE| Irish only identity
45| 1375| NATIDE| Other European
45| 1376| NATIDE| EU countries
45| 1377| NATIDE| Member countries in March 2001
45| 1378| NATIDE| French
45| 1379| NATIDE| German
45| 1380| NATIDE| Italian
45| 1381| NATIDE| Portuguese
45| 1382| NATIDE| Spanish (including Canary Islander)
45| 1383| NATIDE| Other member countries in March 2001
45| 1384| NATIDE| Accession countries April 2001 to March 2011
45| 1385| NATIDE| Lithuanian
45| 1386| NATIDE| Polish
45| 1387| NATIDE| Romanian
45| 1388| NATIDE| Other EU accession countries
45| 1389| NATIDE| Rest of Europe
45| 1390| NATIDE| Turkish
45| 1391| NATIDE| Other European
45| 1392| NATIDE| African
45| 1393| NATIDE| North African
45| 1394| NATIDE| Central and Western African
45| 1395| NATIDE| Ghanaian
45| 1396| NATIDE| Nigerian
45| 1397| NATIDE| Other Central and Western African
45| 1398| NATIDE| South and Eastern African
45| 1399| NATIDE| Kenyan
45| 1400| NATIDE| Somali
45| 1401| NATIDE| South African
45| 1402| NATIDE| Zimbabwean
45| 1403| NATIDE| Other South and Eastern African
45| 1404| NATIDE| Middle Eastern and Asian
45| 1405| NATIDE| Middle Eastern
45| 1406| NATIDE| Iranian
45| 1407| NATIDE| Iraqi
45| 1408| NATIDE| Other Middle Eastern
45| 1409| NATIDE| Eastern Asian
45| 1410| NATIDE| Chinese
45| 1411| NATIDE| Hong Kong Chinese
45| 1412| NATIDE| Japanese
45| 1413| NATIDE| Other Eastern Asian
45| 1414| NATIDE| Southern Asian
45| 1415| NATIDE| Afghan
45| 1416| NATIDE| Bangladeshi
45| 1417| NATIDE| Indian
45| 1418| NATIDE| Pakistani
45| 1419| NATIDE| Sri Lankan
45| 1420| NATIDE| Other Southern Asian
45| 1421| NATIDE| Southern-East Asian
45| 1422| NATIDE| Filipino
45| 1423| NATIDE| Malaysian
45| 1424| NATIDE| Singaporean
45| 1425| NATIDE| Other South-East Asian
45| 1426| NATIDE| Central Asian
45| 1427| NATIDE| Asian (not otherwise specified)
45| 1428| NATIDE| American and Caribbean
45| 1429| NATIDE| North American
45| 1430| NATIDE| Canadian
45| 1431| NATIDE| US Citizen
45| 1432| NATIDE| Other North American
45| 1433| NATIDE| Central American
45| 1434| NATIDE| South American
45| 1435| NATIDE| Caribbean
45| 1436| NATIDE| Jamaican
45| 1437| NATIDE| Other Caribbean
45| 1438| NATIDE| Antarctican and Oceanian
45| 1439| NATIDE| Australasian
45| 1440| NATIDE| Australian
45| 1441| NATIDE| New Zealander
45| 1442| NATIDE| Other Australasian
45| 1443| NATIDE| Other Oceanian
45| 1444| NATIDE| Other
48| 1445| NSSEC| Total: NS-SeC (National Statistics Socio-economic Classification)
48| 1446| NSSEC| 1. Higher managerial| administrative and professional occupations
48| 1447| NSSEC| 1.1 Large employers and higher managerial and administrative occupations
48| 1448| NSSEC| 1.2 Higher professional occupations
48| 1449| NSSEC| 2. Lower managerial| administrative and professional occupations
48| 1450| NSSEC| 3. Intermediate occupations
48| 1451| NSSEC| 4. Small employers and own account workers
48| 1452| NSSEC| 5. Lower supervisory and technical occupations
48| 1453| NSSEC| 6. Semi-routine occupations
48| 1454| NSSEC| 7. Routine occupations
48| 1455| NSSEC| 8. Never worked and long-term unemployed
48| 1456| NSSEC| L14.1 Never worked
48| 1457| NSSEC| L14.2 Long-term unemployed
48| 1458| NSSEC| Not classified
48| 1459| NSSEC| L15 Full-time students
48| 1460| NSSEC| L17 Not classifiable for other reasons
48| 1461| NSSEC| L1 Employers in large establishments
48| 1462| NSSEC| L2 Higher managerial and administrative occupations
48| 1463| NSSEC| L3.1 Traditional employees
48| 1464| NSSEC| L3.2 New employees
48| 1465| NSSEC| L3.3 Traditional self-employed
48| 1466| NSSEC| L3.4 New self-employed
48| 1467| NSSEC| L4 Lower professional and higher technical occupations
48| 1468| NSSEC| L4.1 Traditional employees
48| 1469| NSSEC| L4.2 New employees
48| 1470| NSSEC| L4.3 Traditional self-employed
48| 1471| NSSEC| L4.4 New self-employed
48| 1472| NSSEC| L5 Lower managerial and administrative occupations
48| 1473| NSSEC| L6 Higher supervisory occupations
48| 1474| NSSEC| L7.1 Intermediate clerical and administrative occupations
48| 1475| NSSEC| L7.2 Intermediate sales and service occupations
48| 1476| NSSEC| L7.3 Intermediate technical and auxiliary occupations
48| 1477| NSSEC| L7.4 Intermediate engineering occupations
48| 1478| NSSEC| L8 Employers in small organisations
48| 1479| NSSEC| L8.1 Employers in small establishments in industry| commerce| services etc.
48| 1480| NSSEC| L8.2 Employers in small establishments in agriculture
48| 1481| NSSEC| L9 Own account workers
48| 1482| NSSEC| L9.1 Own account workers (non-professional)
48| 1483| NSSEC| L9.2 Own account workers (agriculture)
48| 1484| NSSEC| L10 Lower supervisory occupations
48| 1485| NSSEC| L11 Lower technical occupations
48| 1486| NSSEC| L11.1 Lower technical craft occupations
48| 1487| NSSEC| L11.2 Lower technical process operative occupations
48| 1488| NSSEC| L12.1 Semi-routine sales occupations
48| 1489| NSSEC| L12.2 Semi-routine service occupations
48| 1490| NSSEC| L12.3 Semi-routine technical occupations
48| 1491| NSSEC| L12.4 Semi-routine operative occupations
48| 1492| NSSEC| L12.5 Semi-routine agricultural occupations
48| 1493| NSSEC| L12.6 Semi-routine clerical occupations
48| 1494| NSSEC| L12.7 Semi-routine childcare occupations
48| 1495| NSSEC| L13.1 Routine sales and service occupations
48| 1496| NSSEC| L13.2 Routine production occupations
48| 1497| NSSEC| L13.3 Routine technical occupations
48| 1498| NSSEC| L13.4 Routine operative occupations
48| 1499| NSSEC| L13.5 Routine agricultural occupations
49| 1500| NSSHRP| Total: NS-SeC (National Statistics Socio-economic Classification) of Household Reference Person
49| 1501| NSSHRP| 1. Higher managerial| administrative and professional occupations
49| 1502| NSSHRP| 1.1 Large employers and higher managerial and administrative occupations
49| 1503| NSSHRP| L1 Employers in large establishments
49| 1504| NSSHRP| L2 Higher managerial and administrative occupations
49| 1505| NSSHRP| 1.2 Higher professional occupations
49| 1506| NSSHRP| L3.1 Traditional employees
49| 1507| NSSHRP| L3.2 New employees
49| 1508| NSSHRP| L3.3 Traditional self-employed
49| 1509| NSSHRP| L3.4 New self-employed
49| 1510| NSSHRP| 2. Lower managerial| administrative and professional occupations
49| 1511| NSSHRP| L4 Lower professional and higher technical occupations
49| 1512| NSSHRP| L4.1 Traditional employees
49| 1513| NSSHRP| L4.2 New employees
49| 1514| NSSHRP| L4.3 Traditional self-employed
49| 1515| NSSHRP| L4.4 New self-employed
49| 1516| NSSHRP| L5 Lower managerial and administrative occupations
49| 1517| NSSHRP| L6 Higher supervisory occupations
49| 1518| NSSHRP| 3. Intermediate occupations
49| 1519| NSSHRP| L7.1 Intermediate clerical and administrative occupations
49| 1520| NSSHRP| L7.2 Intermediate sales and service occupations
49| 1521| NSSHRP| L7.3 Intermediate technical and auxiliary occupations
49| 1522| NSSHRP| L7.4 Intermediate engineering occupations
49| 1523| NSSHRP| 4. Small employers and own account workers
49| 1524| NSSHRP| L8 Employers in small organisations
49| 1525| NSSHRP| L8.1 Employers in small establishments in industry| commerce| services etc.
49| 1526| NSSHRP| L8.2 Employers in small establishments in agriculture
49| 1527| NSSHRP| L9 Own account workers
49| 1528| NSSHRP| L9.1 Own account workers (non-professional)
49| 1529| NSSHRP| L9.2 Own account workers (agriculture)
49| 1530| NSSHRP| 5. Lower supervisory and technical occupations
49| 1531| NSSHRP| L10 Lower supervisory occupations
49| 1532| NSSHRP| L11 Lower technical occupations
49| 1533| NSSHRP| L11.1 Lower technical craft occupations
49| 1534| NSSHRP| L11.2 Lower technical process operative occupations
49| 1535| NSSHRP| 6. Semi-routine occupations
49| 1536| NSSHRP| L12.1 Semi-routine sales occupations
49| 1537| NSSHRP| L12.2 Semi-routine service occupations
49| 1538| NSSHRP| L12.3 Semi-routine technical occupations
49| 1539| NSSHRP| L12.4 Semi-routine operative occupations
49| 1540| NSSHRP| L12.5 Semi-routine agricultural occupations
49| 1541| NSSHRP| L12.6 Semi-routine clerical occupations
49| 1542| NSSHRP| L12.7 Semi-routine childcare occupations
49| 1543| NSSHRP| 7. Routine occupations
49| 1544| NSSHRP| L13.1 Routine sales and service occupations
49| 1545| NSSHRP| L13.2 Routine production occupations
49| 1546| NSSHRP| L13.3 Routine technical occupations
49| 1547| NSSHRP| L13.4 Routine operative occupations
49| 1548| NSSHRP| L13.5 Routine agricultural occupations
49| 1549| NSSHRP| 8. Never worked and long-term unemployed
49| 1550| NSSHRP| L14.1 Never worked
49| 1551| NSSHRP| L14.2 Long-term unemployed
49| 1552| NSSHRP| Not classified
49| 1553| NSSHRP| L15 Full-time students
49| 1554| NSSHRP| L17 Not classifiable for other reasons
50| 1555| NUMAHH| Total: Number of adults in household
50| 1556| NUMAHH| 1 adult in household
50| 1557| NUMAHH| 0 or multiple adults in household
51| 1558| NUMBED| Average number of bedrooms per household
51| 1559| NUMBED| All categories: Number of bedrooms
51| 1560| NUMBED| No bedrooms
51| 1561| NUMBED| 1 bedroom
51| 1562| NUMBED| 2 bedrooms
51| 1563| NUMBED| 3 bedrooms
51| 1564| NUMBED| 4 bedrooms
51| 1565| NUMBED| 5 or more bedrooms
46| 1566| NPBHH| All categories: Number of persons per bedroom in household
46| 1567| NPBHH| Up to 0.5 persons per bedroom
46| 1568| NPBHH| Over 0.5 and up to 1.0 persons per bedroom
46| 1569| NPBHH| Over 1.0 and up to 1.5 persons per bedroom
46| 1570| NPBHH| Over 1.5 persons per bedroom
47| 1571| NPRHH| All categories: Number of persons per room in household
47| 1572| NPRHH| Up to 0.5 persons per room
47| 1573| NPRHH| Over 0.5 and up to 1.0 persons per room
47| 1574| NPRHH| Over 1.0 and up to 1.5 persons per room
47| 1575| NPRHH| Over 1.5 persons per room
52| 1576| NUMRMS| Average number of rooms per household
52| 1577| NUMRMS| All categories: Number of rooms
52| 1578| NUMRMS| 1 room
52| 1579| NUMRMS| 2 rooms
52| 1580| NUMRMS| 3 rooms
52| 1581| NUMRMS| 4 rooms
52| 1582| NUMRMS| 5 rooms
52| 1583| NUMRMS| 6 rooms
52| 1584| NUMRMS| 7 rooms
52| 1585| NUMRMS| 8 rooms
52| 1586| NUMRMS| 9 or more rooms
67| 1587| UCRATR| Occupancy rating (rooms) of -1 or less
67| 1588| UCRATR| Total: Occupancy rating (rooms)
67| 1589| UCRATR| Occupancy rating (rooms) of +2 or more
67| 1590| UCRATR| Occupancy rating (rooms) of +1
67| 1591| UCRATR| Occupancy rating (rooms) of 0
67| 1592| UCRATR| Occupancy rating (rooms) of -1
67| 1593| UCRATR| Occupancy rating (rooms) of -2 or less
54| 1594| OCRATB| Occupancy rating (bedrooms) of -1 or less
54| 1595| OCRATB| Total: Occupancy rating (bedrooms)
54| 1596| OCRATB| Occupancy rating (bedrooms) of +2 or more
54| 1597| OCRATB| Occupancy rating (bedrooms) of +1
54| 1598| OCRATB| Occupancy rating (bedrooms) of 0
54| 1599| OCRATB| Occupancy rating (bedrooms) of -1
54| 1600| OCRATB| Occupancy rating (bedrooms) of -2 or less
53| 1601| OCCUP| Total: Occupation
53| 1602| OCCUP| 1. Managers| directors and senior officials
53| 1603| OCCUP| 2. Professional occupations
53| 1604| OCCUP| 3. Associate professional and technical occupations
53| 1605| OCCUP| 4. Administrative and secretarial occupations
53| 1606| OCCUP| 5. Skilled trades occupations
53| 1607| OCCUP| 6. Caring| leisure and other service occupations
53| 1608| OCCUP| 7. Sales and customer service occupations
53| 1609| OCCUP| 8. Process| plant and machine operatives
53| 1610| OCCUP| 9. Elementary occupations
77| 1611| OGRPMIN| Total: Occupation (minor groups)
77| 1612| OGRPMIN| 1. Managers| directors and senior officials
77| 1613| OGRPMIN| 11. Corporate managers and directors
77| 1614| OGRPMIN| 111. Chief Executives and Senior Officials
77| 1615| OGRPMIN| 112. Production Managers and Directors
77| 1616| OGRPMIN| 113. Functional Managers and Directors
77| 1617| OGRPMIN| 115. Financial Institution Managers and Directors
77| 1618| OGRPMIN| 116. Managers and Directors in Transport and Logistics
77| 1619| OGRPMIN| 117. Senior Officers in Protective Services
77| 1620| OGRPMIN| 118. Health and Social Services Managers and Directors
77| 1621| OGRPMIN| 119. Managers and Directors in Retail and Wholesale
77| 1622| OGRPMIN| 12. Other managers and proprietors
77| 1623| OGRPMIN| 121. Managers and Proprietors in Agriculture Related Services
77| 1624| OGRPMIN| 122. Managers and Proprietors in Hospitality and Leisure Services
77| 1625| OGRPMIN| 124. Managers and Proprietors in Health and Care Services
77| 1626| OGRPMIN| 125. Managers and Proprietors in Other Services
77| 1627| OGRPMIN| 2. Professional occupations
77| 1628| OGRPMIN| 21. Science| research| engineering and technology professionals
77| 1629| OGRPMIN| 211. Natural and Social Science Professionals
77| 1630| OGRPMIN| 212. Engineering Professionals
77| 1631| OGRPMIN| 213. Information Technology and Telecommunications Professionals
77| 1632| OGRPMIN| 214. Conservation and Environment Professionals
77| 1633| OGRPMIN| 215. Research and Development Managers
77| 1634| OGRPMIN| 22. Health professionals
77| 1635| OGRPMIN| 221. Health Professionals
77| 1636| OGRPMIN| 222. Therapy Professionals
77| 1637| OGRPMIN| 223. Nursing and Midwifery Professionals
77| 1638| OGRPMIN| 23. Teaching and educational professionals
77| 1639| OGRPMIN| 231. Teaching and Educational Professionals
77| 1640| OGRPMIN| 24. Business| media and public service professionals
77| 1641| OGRPMIN| 241. Legal Professionals
77| 1642| OGRPMIN| 242. Business| Research and Administrative Professionals
77| 1643| OGRPMIN| 243. Architects| Town Planners and Surveyors
77| 1644| OGRPMIN| 244. Welfare Professionals
77| 1645| OGRPMIN| 245. Librarians and Related Professionals
77| 1646| OGRPMIN| 246. Quality and Regulatory Professionals
77| 1647| OGRPMIN| 247. Media Professionals
77| 1648| OGRPMIN| 3. Associate professional and technical occupations
77| 1649| OGRPMIN| 31. Science| engineering and technology associate professionals
77| 1650| OGRPMIN| 311. Science| Engineering and Production Technicians
77| 1651| OGRPMIN| 312. Draughtspersons and Related Architectural Technicians
77| 1652| OGRPMIN| 313. Information Technology Technicians
77| 1653| OGRPMIN| 32. Health and social care associate professionals
77| 1654| OGRPMIN| 321. Health Associate Professionals
77| 1655| OGRPMIN| 323. Welfare and Housing Associate Professionals
77| 1656| OGRPMIN| 33. Protective service occupations
77| 1657| OGRPMIN| 331. Protective Service Occupations
77| 1658| OGRPMIN| 34. Culture| media and sports occupations
77| 1659| OGRPMIN| 341. Artistic| Literary and Media Occupations
77| 1660| OGRPMIN| 342. Design Occupations
77| 1661| OGRPMIN| 344. Sports and Fitness Occupations
77| 1662| OGRPMIN| 35. Business and public service associate professionals
77| 1663| OGRPMIN| 351. Transport Associate Professionals
77| 1664| OGRPMIN| 352. Legal Associate Professionals
77| 1665| OGRPMIN| 353. Business| Finance and Related Associate Professionals
77| 1666| OGRPMIN| 354. Sales| Marketing and Related Associate Professionals
77| 1667| OGRPMIN| 355. Conservation and Environmental associate professionals
77| 1668| OGRPMIN| 356. Public Services and Other Associate Professionals
77| 1669| OGRPMIN| 4. Administrative and secretarial occupations
77| 1670| OGRPMIN| 41. Administrative occupations
77| 1672| OGRPMIN| 411. Government and Related Organisations
77| 1673| OGRPMIN| 412. Finance
77| 1674| OGRPMIN| 413. Records
77| 1675| OGRPMIN| 415. Other Administrative Occupations
77| 1676| OGRPMIN| 416. Office Managers and Supervisors
77| 1677| OGRPMIN| 42. Secretarial and related occupations
77| 1678| OGRPMIN| 421. Secretarial and Related Occupations
77| 1679| OGRPMIN| 5. Skilled trades occupations
77| 1680| OGRPMIN| 51. Skilled agricultural and related trades
77| 1681| OGRPMIN| 511. Agricultural and Related Trades
77| 1682| OGRPMIN| 52. Skilled metal| electrical and electronic trades
77| 1683| OGRPMIN| 521. Metal Forming| Welding and Related Trades
77| 1684| OGRPMIN| 522. Metal Machining| Fitting and Instrument Making Trades
77| 1685| OGRPMIN| 523. Vehicle Trades
77| 1686| OGRPMIN| 524. Electrical and Electronic Trades
77| 1687| OGRPMIN| 525. Skilled Metal| Electrical and Electronic Trades Supervisors
77| 1688| OGRPMIN| 53. Skilled construction and building trades
77| 1689| OGRPMIN| 531. Construction and Building Trades
77| 1690| OGRPMIN| 532. Building Finishing Trades
77| 1691| OGRPMIN| 533. Construction and Building Trades Supervisors
77| 1692| OGRPMIN| 54. Textiles| printing and other skilled trades
77| 1693| OGRPMIN| 541. Textiles and Garments Trades
77| 1694| OGRPMIN| 542. Printing Trades
77| 1695| OGRPMIN| 543. Food Preparation and Hospitality Trades
77| 1696| OGRPMIN| 544. Other Skilled Trades
77| 1697| OGRPMIN| 6. Caring| leisure and other service occupations
77| 1698| OGRPMIN| 61. Caring personal service occupations
77| 1699| OGRPMIN| 612. Childcare and Related Personal Services
77| 1700| OGRPMIN| 613. Animal Care and Control Services
77| 1701| OGRPMIN| 614. Caring Personal Services
77| 1702| OGRPMIN| 62. Leisure| travel and related personal service occupations
77| 1703| OGRPMIN| 621. Leisure and Travel Services
77| 1704| OGRPMIN| 622. Hairdressers and Related Services
77| 1705| OGRPMIN| 623. Housekeeping and Related Services
77| 1706| OGRPMIN| 624. Cleaning and Housekeeping Managers and Supervisors
77| 1707| OGRPMIN| 7. Sales and customer service occupations
77| 1708| OGRPMIN| 71. Sales occupations
77| 1709| OGRPMIN| 711. Sales Assistants and Retail Cashiers
77| 1710| OGRPMIN| 712. Sales Related Occupations
77| 1711| OGRPMIN| 713. Sales Supervisors
77| 1712| OGRPMIN| 72. Customer service occupations
77| 1713| OGRPMIN| 721. Customer Service Occupations
77| 1714| OGRPMIN| 722. Customer Service Managers and Supervisors
77| 1715| OGRPMIN| 8. Process| plant and machine operatives
77| 1716| OGRPMIN| 81. Process| plant and machine operatives
77| 1717| OGRPMIN| 811. Process Operatives
77| 1718| OGRPMIN| 812. Plant and Machine Operatives
77| 1719| OGRPMIN| 813. Assemblers and Routine Operatives
77| 1720| OGRPMIN| 814. Construction Operatives
77| 1721| OGRPMIN| 82. Transport and mobile machine drivers and operatives
77| 1722| OGRPMIN| 821. Road Transport Drivers
77| 1723| OGRPMIN| 822. Mobile Machine Drivers and Operatives
77| 1724| OGRPMIN| 823. Other Drivers and Transport Operatives
77| 1725| OGRPMIN| 9. Elementary occupations
77| 1726| OGRPMIN| 91. Elementary trades and related occupations
77| 1727| OGRPMIN| 911. Elementary Agricultural Occupations
77| 1728| OGRPMIN| 912. Elementary Construction Occupations
77| 1729| OGRPMIN| 913. Elementary Process Plant Occupations
77| 1730| OGRPMIN| 92. Elementary administration and service occupations
77| 1731| OGRPMIN| 921. Elementary Administration Occupations
77| 1732| OGRPMIN| 923. Elementary Cleaning Occupations
77| 1733| OGRPMIN| 924. Elementary Security Occupations
77| 1734| OGRPMIN| 925. Elementary Sales Occupations
77| 1735| OGRPMIN| 926. Elementary Storage Occupations
77| 1736| OGRPMIN| 927. Other Elementary Services Occupations
55| 1737| PASHLD| Total: Passports held (principal)
55| 1738| PASHLD| Europe
55| 1739| PASHLD| United Kingdom
55| 1740| PASHLD| Republic of Ireland
55| 1741| PASHLD| Other Europe
55| 1742| PASHLD| EU countries
55| 1743| PASHLD| Member countries in March 2001
55| 1744| PASHLD| France
55| 1745| PASHLD| Germany
55| 1746| PASHLD| Italy
55| 1747| PASHLD| Portugal
55| 1748| PASHLD| Spain
55| 1749| PASHLD| Other member countries in March 2001
55| 1750| PASHLD| Accession countries April 2001 to March 2011
55| 1751| PASHLD| Lithuania
55| 1752| PASHLD| Poland
55| 1753| PASHLD| Romania
55| 1754| PASHLD| Other EU accession countries
55| 1755| PASHLD| Rest of Europe
55| 1756| PASHLD| Turkey
55| 1757| PASHLD| Other Europe
55| 1758| PASHLD| Africa
55| 1759| PASHLD| North Africa
55| 1760| PASHLD| Central and Western Africa
55| 1761| PASHLD| Ghana
55| 1762| PASHLD| Nigeria
55| 1763| PASHLD| Other Central and Western Africa
55| 1764| PASHLD| South and Eastern Africa
55| 1765| PASHLD| Kenya
55| 1766| PASHLD| Somalia
55| 1767| PASHLD| South Africa
55| 1768| PASHLD| Zimbabwe
55| 1769| PASHLD| Other South and Eastern Africa
55| 1770| PASHLD| Middle East and Asia
55| 1771| PASHLD| Middle East
55| 1772| PASHLD| Iran
55| 1773| PASHLD| Iraq
55| 1774| PASHLD| Other Middle East
55| 1775| PASHLD| Eastern Asia
55| 1776| PASHLD| China
55| 1777| PASHLD| Hong Kong (Special Administrative Region of China)
55| 1778| PASHLD| Japan
55| 1779| PASHLD| Other Eastern Asia
55| 1780| PASHLD| Southern Asia
55| 1781| PASHLD| Afghanistan
55| 1782| PASHLD| Bangladesh
55| 1783| PASHLD| India
55| 1784| PASHLD| Pakistan
55| 1785| PASHLD| Sri Lanka
55| 1786| PASHLD| Other Southern Asia
55| 1787| PASHLD| South-East Asia
55| 1788| PASHLD| Malaysia
55| 1789| PASHLD| Philippines
55| 1790| PASHLD| Singapore
55| 1791| PASHLD| Other South-East Asia
55| 1792| PASHLD| Central Asia
55| 1793| PASHLD| The Americas and the Caribbean
55| 1794| PASHLD| North America
55| 1795| PASHLD| Canada
55| 1796| PASHLD| United States
55| 1797| PASHLD| Central America
55| 1798| PASHLD| South America
55| 1799| PASHLD| The Caribbean
55| 1800| PASHLD| Jamaica
55| 1801| PASHLD| Other Caribbean
55| 1802| PASHLD| Antarctica and Oceania
55| 1803| PASHLD| Australasia
55| 1804| PASHLD| Australia
55| 1805| PASHLD| New Zealand
55| 1806| PASHLD| Other Oceania
55| 1807| PASHLD| British Overseas Territories
55| 1808| PASHLD| No passport held
75| 1809| PPHALL| No passport held
75| 1810| PPHALL| United Kingdom
75| 1811| PPHALL| Republic of Ireland
75| 1812| PPHALL| Other Europe
75| 1813| PPHALL| EU countries
75| 1814| PPHALL| Non-EU countries
75| 1815| PPHALL| Africa
75| 1816| PPHALL| Middle East and Asia
75| 1817| PPHALL| North America and the Caribbean
75| 1818| PPHALL| Central America
75| 1819| PPHALL| South America
75| 1820| PPHALL| Antarctica and Oceania
75| 1821| PPHALL| British Overseas Territories
56| 1822| PCOMST| Total: Position in communal establishment
56| 1823| PCOMST| Resident
56| 1824| PCOMST| Staff or owner
56| 1825| PCOMST| Family member or partner of staff or owner
57| 1826| PROENG| Total: Proficiency in English
57| 1827| PROENG| Main language is English (English or Welsh in Wales)
57| 1828| PROENG| Main language is not English (English or Welsh in Wales)
57| 1829| PROENG| Can speak English very well
57| 1830| PROENG| Can speak English well
57| 1831| PROENG| Cannot speak English well
57| 1832| PROENG| Cannot speak English
58| 1833| PRUNCA| Provides no unpaid care
58| 1834| PRUNCA| Provides 1 to 19 hours unpaid care a week
58| 1835| PRUNCA| Provides 20 to 49 hours unpaid care a week
58| 1836| PRUNCA| Provides 50 or more hours unpaid care a week
58| 1837| PRUNCA| All categories: Provision of unpaid care
59| 1838| QUALGA| Total: Qualifications gained
59| 1839| QUALGA| No qualifications
59| 1840| QUALGA| 1-4 O levels/CSE/GCSEs (any grades)| Entry Level| Foundation Diploma
59| 1841| QUALGA| NVQ Level 1| Foundation GNVQ| Basic Skills
59| 1842| QUALGA| 5+ O level (Passes)/CSEs (Grade 1)/GCSEs (Grades A*-C)| School Certificate| 1 A level/2-3 AS levels/VCEs| Higher Diploma| Welsh Baccalaureate Intermediate Diploma
59| 1843| QUALGA| NVQ Level 2| Intermediate GNVQ| City and Guilds Craft| BTEC First/General Diploma| RSA Diploma
59| 1844| QUALGA| Apprenticeship
59| 1845| QUALGA| 2+ A levels/VCEs| 4+ AS levels| Higher School Certificate| Progression/Advanced Diploma| Welsh Baccalaureate Advanced Diploma
59| 1846| QUALGA| NVQ Level 3| Advanced GNVQ| City and Guilds Advanced Craft| ONC| OND| BTEC National| RSA Advanced Diploma
59| 1847| QUALGA| Degree (for example BA| BSc)| Higher degree (for example MA| PhD| PGCE)
59| 1848| QUALGA| NVQ Level 4-5| HNC| HND| RSA Higher Diploma| BTEC Higher Level
59| 1849| QUALGA| Professional qualifications (for example teaching| nursing| accountancy)
59| 1850| QUALGA| Other vocational/work-related qualifications
59| 1851| QUALGA| Foreign qualifications
60| 1852| RELIG| Total: Religion
60| 1853| RELIG| Christian
60| 1854| RELIG| Buddhist
60| 1855| RELIG| Hindu
60| 1856| RELIG| Jewish
60| 1857| RELIG| Muslim
60| 1858| RELIG| Sikh
60| 1859| RELIG| Other religion
60| 1860| RELIG| No religion
60| 1861| RELIG| Religion not stated
78| 1862| RELIGDET| Total: Religion (detailed)
78| 1863| RELIGDET| Christian
78| 1864| RELIGDET| Buddhist
78| 1865| RELIGDET| Hindu
78| 1866| RELIGDET| Jewish
78| 1867| RELIGDET| Muslim
78| 1868| RELIGDET| Sikh
78| 1869| RELIGDET| Other religion
78| 1870| RELIGDET| Animism
78| 1871| RELIGDET| Baha'i
78| 1872| RELIGDET| Believe in God
78| 1873| RELIGDET| Brahma Kumari
78| 1874| RELIGDET| Chinese Religion
78| 1875| RELIGDET| Church of All Religion
78| 1876| RELIGDET| Confucianist
78| 1877| RELIGDET| Deist
78| 1878| RELIGDET| Druid
78| 1879| RELIGDET| Druze
78| 1880| RELIGDET| Eckankar
78| 1881| RELIGDET| Heathen
78| 1882| RELIGDET| Jain
78| 1883| RELIGDET| Mixed Religion
78| 1884| RELIGDET| Mysticism
78| 1885| RELIGDET| Native American Church
78| 1886| RELIGDET| New Age
78| 1887| RELIGDET| Occult
78| 1888| RELIGDET| Own Belief System
78| 1889| RELIGDET| Pagan
78| 1890| RELIGDET| Pantheism
78| 1891| RELIGDET| Rastafarian
78| 1892| RELIGDET| Ravidassia
78| 1893| RELIGDET| Reconstructionist
78| 1894| RELIGDET| Satanism
78| 1895| RELIGDET| Scientology
78| 1896| RELIGDET| Shamanism
78| 1897| RELIGDET| Shintoism
78| 1898| RELIGDET| Spiritual
78| 1899| RELIGDET| Spiritualist
78| 1900| RELIGDET| Taoist
78| 1901| RELIGDET| Theism
78| 1902| RELIGDET| Thelemite
78| 1903| RELIGDET| Traditional African Religion
78| 1904| RELIGDET| Unification Church
78| 1905| RELIGDET| Universalist
78| 1906| RELIGDET| Vodun
78| 1907| RELIGDET| Wicca
78| 1908| RELIGDET| Witchcraft
78| 1909| RELIGDET| Zoroastrian
78| 1910| RELIGDET| Other religions
78| 1911| RELIGDET| No religion
78| 1912| RELIGDET| No religion
78| 1913| RELIGDET| Agnostic
78| 1914| RELIGDET| Atheist
78| 1915| RELIGDET| Free Thinker
78| 1916| RELIGDET| Heavy Metal
78| 1917| RELIGDET| Humanist
78| 1918| RELIGDET| Jedi Knight
78| 1919| RELIGDET| Realist
78| 1920| RELIGDET| Religion not stated
62| 1921| RESTYP| Total: Residence type
62| 1922| RESTYP| Lives in a household
62| 1923| RESTYP| Lives in a communal establishment
62| 1924| RESTYP| Communal establishments with persons sleeping rough enumerated
63| 1927| SECADD| Total: Second address
63| 1928| SECADD| No second address
63| 1929| SECADD| Second address within the UK
63| 1930| SECADD| Second address outside the UK
64| 1931| SEX| Total: Sex
64| 1932| SEX| Males
64| 1933| SEX| Females
64| 1934| SEX| Male
64| 1935| SEX| Female
66| 1936| TENURE| Total: Tenure
66| 1937| TENURE| Owned
66| 1938| TENURE| Owned outright
66| 1939| TENURE| Owned with a mortgage or loan
66| 1940| TENURE| Shared ownership (part owned and part rented)
66| 1941| TENURE| Social rented
66| 1942| TENURE| Rented from council (Local Authority)
66| 1943| TENURE| Other
66| 1944| TENURE| Private rented
66| 1945| TENURE| Private landlord or letting agency
66| 1946| TENURE| Other
66| 1947| TENURE| Living rent-free
66| 1948| TENURE| Other social rented
66| 1949| TENURE| Employer of a household member
66| 1950| TENURE| Relative or friend of household member
66| 1951| TENURE| Rented from council (Local Authority)
66| 1952| TENURE| Other social rented
65| 1953| TCENHHH| Total: Type of central heating in household
65| 1954| TCENHHH| No central heating
65| 1955| TCENHHH| Does have central heating
65| 1956| TCENHHH| Gas central heating
65| 1957| TCENHHH| Electric (including storage heaters) central heating
65| 1958| TCENHHH| Oil central heating
65| 1959| TCENHHH| Solid fuel (for example wood| coal) central heating
65| 1960| TCENHHH| Other central heating
65| 1961| TCENHHH| Two or more types of central heating
68| 1962| UNIT| Persons
68| 1963| UNIT| Hectares
68| 1964| UNIT| Households
68| 1965| UNIT| Dwellings
68| 1966| UNIT| Rooms
68| 1967| UNIT| Bedrooms
68| 1968| UNIT| Cars or vans
68| 1969| UNIT| Communal establishments
68| 1970| UNIT| Families
68| 1971| UNIT| Household spaces
69| 1972| URESPOP| Schoolchild or full-time student aged 4 and over at their non-term-time address
69| 1973| URESPOP| Area (Hectares)
69| 1974| URESPOP| Density (number of persons per Hectare)
69| 1975| URESPOP| All usual residents in households
69| 1976| URESPOP| All households
69| 1977| URESPOP| No adults in employment in household
69| 1978| URESPOP| All usual residents
69| 1979| URESPOP| All usual residents in communal establishments
69| 1980| URESPOP| Schoolchildren and full-time students at their non-term-time address
69| 1981| URESPOP| All families in households
69| 1982| URESPOP| All dependent children in households
69| 1983| URESPOP| All usual residents employed in the Armed Forces
71| 1984| WELLANGP| Total: Welsh language profile
71| 1985| WELLANGP| Can understand spoken Welsh only
71| 1986| WELLANGP| Can speak Welsh
71| 1987| WELLANGP| Can speak| read and write Welsh
71| 1988| WELLANGP| One or more skills in Welsh
72| 1989| WELLANGS| No skills in Welsh
72| 1990| WELLANGS| Can understand spoken Welsh only
72| 1991| WELLANGS| Can speak Welsh
72| 1992| WELLANGS| Can speak but cannot read or write Welsh
72| 1993| WELLANGS| Can speak and read but cannot write Welsh
72| 1994| WELLANGS| Can speak| read and write Welsh
72| 1995| WELLANGS| Other combinations of skills in Welsh
72| 1996| WELLANGS| Total: Welsh language skills
72| 1997| WELLANGS| Can understand spoken Welsh
72| 1998| WELLANGS| Can read Welsh
72| 1999| WELLANGS| Can write Welsh
72| 2000| WELLANGS| Can speak| read or write Welsh
79| 2001| IRLANGS| Total: Irish language skills
79| 2002| IRLANGS| Understands but cannot read| write or speak Irish
79| 2003| IRLANGS| Can speak but cannot read or write Irish
79| 2004| IRLANGS| Can speak and read but cannot write Irish
79| 2005| IRLANGS| Can speak| read| write and understand Irish
79| 2006| IRLANGS| Other combination of skills in Irish
79| 2007| IRLANGS| Some ability in Irish
79| 2008| IRLANGS| No ability in Irish
107| 2009| RELSCO| Total: Religion (Scotland)
107| 2010| RELSCO| Church of Scotland
107| 2011| RELSCO| Roman Catholic
74| 2012| YEARLW| Total: Year last worked
74| 2013| YEARLW| In employment
74| 2014| YEARLW| Not in employment
74| 2015| YEARLW| Last worked in 2011
74| 2016| YEARLW| Last worked in 2010
74| 2017| YEARLW| Last worked in 2009
74| 2018| YEARLW| Last worked in 2008
74| 2019| YEARLW| Last worked in 2007
74| 2020| YEARLW| Last worked in 2006
74| 2021| YEARLW| Last worked in 2001-2005
74| 2022| YEARLW| Last worked before 2001
74| 2023| YEARLW| Never worked
73| 2024| YEARAUK| Total: Year of arrival in the UK
73| 2025| YEARAUK| Born in the UK
73| 2026| YEARAUK| Arrived before 1941
73| 2027| YEARAUK| Arrived 1941-1950
73| 2028| YEARAUK| Arrived 1951-1960
73| 2029| YEARAUK| Arrived 1961-1970
73| 2030| YEARAUK| Arrived 1971-1980
73| 2031| YEARAUK| Arrived 1981-1990
73| 2032| YEARAUK| Arrived 1991-2000
73| 2033| YEARAUK| Arrived 2001-2003
73| 2034| YEARAUK| Arrived 2004-2006
73| 2035| YEARAUK| Arrived 2007-2009
73| 2036| YEARAUK| Arrived 2010-2011
3| 2037| AGE| Age 0 to 15
3| 2038| AGE| Age 15 to 19
3| 2039| AGE| Age 16 to 44
3| 2040| AGE| Age 30 to 34
3| 2041| AGE| Age 40 to 44
3| 2042| AGE| Age 35 to 39
3| 2043| AGE| Age 45 to 49
3| 2044| AGE| Age 45 to 64
3| 2045| AGE| Age 5 to 9
3| 2046| AGE| Age 50 to 54
3| 2047| AGE| Age 55 to 59
3| 2048| AGE| Age 65 plus
3| 2049| AGE| Age 65 to 69
3| 2050| AGE| Age 70 to 74
3| 2051| AGE| Age 75 to 79
3| 2052| AGE| Age 80 and over
3| 2053| AGE| Age 80 to 84
3| 2054| AGE| Age 90 to 94
3| 2055| AGE| Age 95 to 99
3| 2056| AGE| Age under 16
3| 2057| AGE| Age under 18
80| 2058| SADLOC| Usual residents elsewhere with a second address in this area
80| 2059| SADLOC| People with a second address per 1|000 usual residents
80| 2060| SADLOC| Usual residents with a second address elsewhere in England and Wales
80| 2061| SADLOC| People with a second address elsewhere in England and Wales per 1|000 usual residents
80| 2062| SADLOC| Usual residents with a second address in Scotland or Northern Ireland
80| 2063| SADLOC| People with a second address in Scotland or Northern Ireland per 1|000 usual residents
80| 2064| SADLOC| Usual residents with a second address outside the UK
80| 2065| SADLOC| People with a second address outside the UK per 1|000 usual residents
81| 2066| SADTYP| Total: Second address type
81| 2067| SADTYP| Holiday
81| 2068| SADTYP| Working
81| 2069| SADTYP| Other
82| 2070| ALTPOP| All non-UK born short-term residents
30| 2071| HHSIZE| 5 or more people in household
69| 2072| URESPOP| Households with usual residents
18| 2074| ECOACT| Student (including economically active students)
12| 2075| COB| Other EU accession countries
12| 2076| COB| Other Eastern Asia
12| 2077| COB| Other Middle East
69| 2078| URESPOP| Full-time students
30| 2079| HHSIZE| Households with at least one usual resident
69| 2080| URESPOP| All usual residents in communal establishments (including people enumerated as sleeping rough. Residents who are staff or owner| and partners of staff or owner are not included for Scotland but are included for England and Wales| and Northern Ireland)
69| 2081| URESPOP| All usual residents in communal establishments (including people enumerated as sleeping rough)
10| 2083| CARVAN| Sum of all cars or vans
66| 2084| TENURE| Other social rented (including accommodation that is rented from a registered social landlord| housing association| housing co-operative or charitable trust)
66| 2085| TENURE| Rented from Northern Ireland Housing Executive (NIHE)
66| 2086| TENURE| Other (including accommodation that is rented from an employer of a household member| relative or friend of a household member| or other non-social rented accommodation)
13| 2088| COMEMT| Medical and care establishment: NHS/HSCT
13| 2089| COMEMT| General hospital
13| 2090| COMEMT| Mental health hospital/unit (including secure units)
13| 2091| COMEMT| Other hospital
13| 2092| COMEMT| Approved premises (probation/bail hostel) [Not applicable in Scotland]
83| 2093| EG_UK| Total: Ethnic Group UK
83| 2094| EG_UK| White
83| 2095| EG_UK| Gypsy/Traveller/Irish Traveller
83| 2096| EG_UK| Mixed/Multiple Ethnic Groups
83| 2097| EG_UK| Asian/Asian British
83| 2098| EG_UK| Indian
83| 2099| EG_UK| Pakistani
83| 2100| EG_UK| Bangladeshi
83| 2101| EG_UK| Chinese
83| 2102| EG_UK| Other Asian
83| 2103| EG_UK| Black/African/Caribbean/Black British
83| 2104| EG_UK| Other Ethnic Group
84| 2105| COBUK| Total: Country of birth UK
84| 2106| COBUK| Europe
84| 2107| COBUK| United Kingdom
84| 2108| COBUK| England
84| 2109| COBUK| Northern Ireland
84| 2110| COBUK| Scotland
84| 2111| COBUK| Wales
84| 2112| COBUK| Not otherwise specified
84| 2113| COBUK| Channel Islands and Isle of Man
84| 2114| COBUK| Republic of Ireland (Includes 'Ireland (not otherwise specified)' for England and Wales)
84| 2115| COBUK| Other Europe
84| 2116| COBUK| EU Countries
84| 2117| COBUK| Germany
84| 2119| COBUK| Lithuania
84| 2120| COBUK| Poland
84| 2121| COBUK| Romania
84| 2122| COBUK| Other Europe: EU countries: Other EU  countries (Includes 'Ireland (not otherwise specified)' for Scotland and Northern Ireland| and 'Cyprus (not othersise specified)' for England and Wales)
84| 2123| COBUK| Rest of Europe
84| 2124| COBUK| Turkey
84| 2125| COBUK| Other Europe (Includes 'Cyprus (not otherwise specified)' for Scotland and Northern Ireland')
84| 2126| COBUK| Africa
84| 2127| COBUK| North Africa(Includes 'Africa (not otherwise specified)')
84| 2128| COBUK| Central and Western Africa
84| 2129| COBUK| Nigeria
84| 2130| COBUK| Other Central and Western Africa
84| 2131| COBUK| South and Eastern Africa
84| 2132| COBUK| Kenya
84| 2133| COBUK| South Africa
84| 2134| COBUK| Zimbabwe
84| 2135| COBUK| Other South and Eastern Africa
84| 2136| COBUK| Middle East and Asia
84| 2137| COBUK| Middle East
84| 2138| COBUK| Iran
84| 2139| COBUK| Other Middle East
84| 2140| COBUK| Eastern Asia
84| 2141| COBUK| China
84| 2142| COBUK| Hong Kong (Special Administrative Region of China)
84| 2143| COBUK| Other Eastern Asia
84| 2144| COBUK| Southern Asia
84| 2145| COBUK| Bangladesh
84| 2146| COBUK| India
84| 2147| COBUK| Pakistan
84| 2148| COBUK| Other Southern Asia
84| 2149| COBUK| South-East Asia
84| 2150| COBUK| Central Asia
84| 2151| COBUK| The Americas and the Caribbean
84| 2152| COBUK| North America and the Caribbean
84| 2153| COBUK| The Caribbean
84| 2154| COBUK| United States of America
84| 2155| COBUK| Other North America
84| 2156| COBUK| Central America
84| 2157| COBUK| South America
84| 2158| COBUK| Antarctica and Oceania
84| 2159| COBUK| Australia
84| 2160| COBUK| Other Antarctia and Oceania
84| 2161| COBUK| Other
82| 2162| ALTPOP| Workday population
3| 2163| AGE| Age 85 and over
42| 2164| MLANDET| Chinese
72| 2165| WELLANGS| Works in Wales but lives in England
107| 2166| RELSCO| Other Christian
82| 2167| ALTPOP| All non-UK born short-term residents in households
85| 2168| HHOLDRP| Household Reference Person (HRP)
69| 2170| URESPOP| All dependent children
69| 2171| URESPOP| All parents
86| 2172| AGEDEP| Total: Age of dependent children
86| 2173| AGEDEP| Age 3 to 4
86| 2174| AGEDEP| Age 5 to 11
86| 2175| AGEDEP| Age 12 to 15
86| 2176| AGEDEP| Age 16 to 18
86| 2177| AGEDEP| Age 3 and over
3| 2178| AGE| Age 3 to 4
69| 2179| URESPOP| All households with schoolchildren or full-time students living away during term-time
69| 2180| URESPOP| All dependent children in one family households
87| 2181| ABWELCH| Total: Ability to speak Welsh
87| 2182| ABWELCH| Can speak Welsh
87| 2183| ABWELCH| Cannot speak Welsh
99| 2184| PARABWE| Total: Parents' ability to speak Welsh
99| 2185| PARABWE| Both members of couple can speak Welsh
99| 2186| PARABWE| One member of couple can speak Welsh
99| 2187| PARABWE| Neither member of couple can speak Welsh
99| 2188| PARABWE| Parent can speak Welsh
99| 2189| PARABWE| Parent cannot speak Welsh
88| 2190| ABDEPWE| Total: Ability of dependent child in a family to speak Welsh
88| 2191| ABDEPWE| Dependent child can speak Welsh
88| 2192| ABDEPWE| Dependent child cannot speak Welsh
1| 2193| ACCTYP| Other
1| 2194| ACCTYP| Flat; maisonette or apartment in a commercial building; or mobile/temporary accommodation
1| 2195| ACCTYP| Flat; maisonette or apartment in a purpose-built block of flats or tenement
1| 2196| ACCTYP| Flat; maisonette or apartment that is part of a converted or shared house (including bed-sits)
1| 2197| ACCTYP| Other
1| 2198| ACCTYP| Flat; maisonette or apartment in a commercial building or mobile/temporary accommodation
1| 2199| ACCTYP| Flat; maisonette or apartment in a purpose-built block of flats or tenement
1| 2200| ACCTYP| Flat; maisonette or apartment that is part of a converted or shared house (including bed-sits)
1| 2201| ACCTYP| Whole house or bungalow
1| 2202| ACCTYP| Detached
1| 2203| ACCTYP| Semi-detached
1| 2204| ACCTYP| Terraced (including end-terrace)
3| 2205| AGE| Age 20 to 21
3| 2206| AGE| Age 22 to 24
3| 2207| AGE| Age under 25
3| 2208| AGE| Age 25 and over
3| 2209| AGE| Age 25 to 49
3| 2210| AGE| Age 35 to 49
3| 2211| AGE| Age 4 to 15
3| 2212| AGE| Age 50 and over
3| 2213| AGE| Age 50 to 64
3| 2214| AGE| Age 0 to 24
3| 2215| AGE| Age 16 to 34
3| 2216| AGE| Age 16 to 49
4| 2217| AGEAUK| Age 0 to 15
4| 2218| AGEAUK| Age 16 to 24
4| 2219| AGEAUK| Age 25 to 34
4| 2220| AGEAUK| Age 35 to 49
4| 2221| AGEAUK| Age 50 to 64
4| 2222| AGEAUK| Age 65 and over
4| 2223| AGEAUK| Born outside the UK
86| 2224| AGEDEP| Age 0 to 2
86| 2225| AGEDEP| Age 10 to 11
86| 2226| AGEDEP| Age 12 to 14
86| 2227| AGEDEP| Age 15
86| 2228| AGEDEP| Age 16
86| 2229| AGEDEP| Age 17
86| 2230| AGEDEP| Age 18
86| 2231| AGEDEP| Age 5 to 7
86| 2232| AGEDEP| Age 8 to 9
90| 2233| AGEFRP| Total: Age of family reference person
90| 2234| AGEFRP| Age under 25
90| 2235| AGEFRP| Age 25 to 34
90| 2236| AGEFRP| Age 35 to 49
90| 2237| AGEFRP| Age 50 to 64
90| 2238| AGEFRP| Age 65 and over
90| 2239| AGEFRP| Age 65 to 74
90| 2240| AGEFRP| Age 75 to 84
90| 2241| AGEFRP| Age 85 and over
91| 2242| AGEYDC| Total: Age of youngest dependent child
91| 2243| AGEYDC| With dependent children
91| 2244| AGEYDC| With no dependent children
91| 2245| AGEYDC| Age 0 to 4
91| 2246| AGEYDC| Age 10 to 15
91| 2247| AGEYDC| Age 12 to 15
91| 2248| AGEYDC| Age 16 to 18
91| 2249| AGEYDC| Age 5 to 11
91| 2250| AGEYDC| Age 5 to 9
10| 2251| CARVAN| 2 or more cars or vans in household
58| 2252| PRUNCA| Provides unpaid care
13| 2253| COMEMT| Other
92| 2254| CONFAM| Total: Concealed family
92| 2255| CONFAM| Concealed family
92| 2256| CONFAM| Couple family
92| 2257| CONFAM| All children non-dependent
92| 2258| CONFAM| Dependent children
92| 2259| CONFAM| No children
92| 2260| CONFAM| Lone parent family
92| 2261| CONFAM| All children non-dependent
92| 2262| CONFAM| Dependent children
92| 2263| CONFAM| Unconcealed family
92| 2264| CONFAM| All children non-dependent
92| 2265| CONFAM| Dependent children
92| 2266| CONFAM| No children
12| 2267| COB| Other Antarctica and Oceania
12| 2268| COB| Antarctica; Oceania (including Australasia); and other
12| 2269| COB| Antarctica and Oceania (including Australasia)
12| 2270| COB| Central and South America
12| 2271| COB| North America and the Caribbean
103| 2272| BORNIN| Born in Wales
103| 2273| BORNIN| Not born in Wales
18| 2274| ECOACT| In employment
18| 2275| ECOACT| Employee
18| 2276| ECOACT| Full-time
18| 2277| ECOACT| Full-time (including full-time students)
18| 2278| ECOACT| 31 to 48 hours worked
18| 2279| ECOACT| 49 or more hours worked
18| 2280| ECOACT| Part-time
18| 2281| ECOACT| Part-time (including full-time students)
18| 2282| ECOACT| 15 hours or less worked
18| 2283| ECOACT| 16 to 30 hours worked
18| 2284| ECOACT| Full-time students
18| 2285| ECOACT| Full-time
18| 2286| ECOACT| 31 to 48 hours worked
18| 2287| ECOACT| 49 or more hours worked
18| 2288| ECOACT| Part-time
18| 2289| ECOACT| 15 hours or less worked
18| 2290| ECOACT| 16 to 30 hours worked
18| 2291| ECOACT| Self-employed
18| 2292| ECOACT| Full-time
18| 2293| ECOACT| Full-time (including full-time students)
18| 2294| ECOACT| 31 to 48 hours worked
18| 2295| ECOACT| 49 or more hours worked
18| 2296| ECOACT| Part-time
18| 2297| ECOACT| Part-time (including full-time students)
18| 2298| ECOACT| 15 hours or less worked
18| 2299| ECOACT| 16 to 30 hours worked
18| 2300| ECOACT| Unemployed (including full-time students)
18| 2301| ECOACT| Full-time students
18| 2302| ECOACT| Unemployed (excluding full-time students)
57| 2303| PROENG| Can speak English very well or well
57| 2304| PROENG| Cannot speak English or cannot speak English well
94| 2305| EGHRP| Total: Ethnic group of Household Reference Person
94| 2306| EGHRP| Asian/Asian British
94| 2307| EGHRP| Bangladeshi
94| 2308| EGHRP| Chinese
94| 2309| EGHRP| Indian
94| 2310| EGHRP| Other Asian
94| 2311| EGHRP| Pakistani
94| 2312| EGHRP| Black/African/Caribbean/Black British
94| 2313| EGHRP| African
94| 2314| EGHRP| Caribbean
94| 2315| EGHRP| Other Black
94| 2316| EGHRP| Mixed/multiple ethnic group
94| 2317| EGHRP| Other Mixed
94| 2318| EGHRP| White and Asian
94| 2319| EGHRP| White and Black African
94| 2320| EGHRP| White and Black Caribbean
94| 2321| EGHRP| Other ethnic group
94| 2322| EGHRP| Any other ethnic group
94| 2323| EGHRP| Arab
94| 2324| EGHRP| White
94| 2325| EGHRP| English/Welsh/Scottish/Northern Irish/British
94| 2326| EGHRP| Gypsy or Irish Traveller
94| 2327| EGHRP| Irish
94| 2328| EGHRP| Other White
93| 2329| EXWHHCO| Total: Extended Welsh household composition
93| 2330| EXWHHCO| One family only
93| 2331| EXWHHCO| Couple household
93| 2332| EXWHHCO| No adults can speak Welsh
93| 2333| EXWHHCO| One adult can speak Welsh - Female
93| 2334| EXWHHCO| One adult can speak Welsh - Male
93| 2335| EXWHHCO| Three or more adults can speak Welsh
93| 2336| EXWHHCO| Two adults can speak Welsh - One male; one female
93| 2337| EXWHHCO| Two adults can speak Welsh - Other combination
93| 2338| EXWHHCO| Lone parent household
93| 2339| EXWHHCO| No adults can speak Welsh
93| 2340| EXWHHCO| One adult can speak Welsh - Female
93| 2341| EXWHHCO| One adult can speak Welsh - Male
93| 2342| EXWHHCO| Two or more adults can speak Welsh
93| 2343| EXWHHCO| Other household types
93| 2344| EXWHHCO| All adults can speak Welsh
93| 2345| EXWHHCO| No adults can speak Welsh
93| 2346| EXWHHCO| Other
24| 2347| FAMSTA| Total: Family status
24| 2348| FAMSTA| Couple family
24| 2349| FAMSTA| Both parents working
24| 2350| FAMSTA| Cohabiting
24| 2351| FAMSTA| Married or in a registered same-sex civil partnership
24| 2352| FAMSTA| No parents working
24| 2353| FAMSTA| One parent working
24| 2354| FAMSTA| Lone-parent family
24| 2355| FAMSTA| Female parent
24| 2356| FAMSTA| Divorced or formerly in a same-sex civil partnership which is now legally dissolved
24| 2357| FAMSTA| Married or in a registered same-sex civil partnership or separated (but still legally married or still legally in a same-sex civil partnership)
24| 2358| FAMSTA| Single (never married or never registered a same-sex civil partnership)
24| 2359| FAMSTA| Widowed or surviving partner from a same-sex civil partnership
24| 2360| FAMSTA| Male parent
24| 2361| FAMSTA| Divorced or formerly in a same-sex civil partnership which is now legally dissolved
24| 2362| FAMSTA| Married or in a registered same-sex civil partnership or separated (but still legally married or still legally in a same-sex civil partnership)
24| 2363| FAMSTA| Single (never married or never registered a same-sex civil partnership)
24| 2364| FAMSTA| Widowed or surviving partner from a same-sex civil partnership
24| 2365| FAMSTA| Parent not working
24| 2366| FAMSTA| Parent working
26| 2367| GENHEA| Bad or very bad health
26| 2368| GENHEA| Very good or good health
26| 2369| GENHEA| Not good health
28| 2370| HHDCOM| Other (including all full-time students and all aged 65 and over)
30| 2371| HHSIZE| 6 or more people in household
32| 2372| HHTYPE| Living in a couple household
32| 2373| HHTYPE| Married or same-sex civil partnership couple household
32| 2374| HHTYPE| Not living in a couple household
100| 2375| HHSFTATT| Total: Schoolchildren or full-time students away during term-time
100| 2376| HHSFTATT| Households with one student away during term-time
100| 2377| HHSFTATT| Aged 18 and over
100| 2378| HHSFTATT| Aged 4 to 17
100| 2379| HHSFTATT| Households with three or more students away during term-time
100| 2380| HHSFTATT| All aged 18 and over
100| 2381| HHSFTATT| All aged 4 to 17
100| 2382| HHSFTATT| Combination of aged 4 to 17 and 18 and over
100| 2383| HHSFTATT| Households with two students away during term-time
100| 2384| HHSFTATT| Both aged 18 and over
100| 2385| HHSFTATT| Both aged 4 to 17
100| 2386| HHSFTATT| One aged 4 to 17 and one 18 and over
35| 2388| INDUST| B| D| E Energy and water
35| 2389| INDUST| G| I Distribution| hotels and restaurants
35| 2390| INDUST| H| J Transport and communication
35| 2391| INDUST| K| L| M| N Financial| real estate| professional and administrative activities
35| 2392| INDUST| O| P| Q Public administration| education and health
102| 2393| NUMLTHPD| 1 person in household with a long-term health problem or disability
102| 2394| NUMLTHPD| 2 or more people in household with a long-term health problem or disability
102| 2395| NUMLTHPD| Total: Number of people in household who may or may not have a long-term health problem or disability
102| 2396| NUMLTHPD| No people in household with a long-term health problem or disability
97| 2397| MAINLAN| African language
97| 2398| MAINLAN| Total: Main language
97| 2399| MAINLAN| Arabic
97| 2400| MAINLAN| East Asian language
97| 2401| MAINLAN| Any other East Asian language
97| 2402| MAINLAN| Chinese
97| 2403| MAINLAN| English (English or Welsh if in Wales)
97| 2404| MAINLAN| French
97| 2405| MAINLAN| Other European language (EU)
97| 2406| MAINLAN| Any other European language
97| 2407| MAINLAN| Polish
97| 2408| MAINLAN| Other European language (non-EU)
97| 2409| MAINLAN| Other language
97| 2410| MAINLAN| Portuguese
97| 2411| MAINLAN| South Asian language
97| 2412| MAINLAN| Any other South Asian language
97| 2413| MAINLAN| Bengali (with Sylheti and Chatgaya)
97| 2414| MAINLAN| Gujarati
97| 2415| MAINLAN| Panjabi
97| 2416| MAINLAN| Tamil
97| 2417| MAINLAN| Urdu
97| 2418| MAINLAN| Spanish
97| 2419| MAINLAN| West/Central Asian language
45| 2420| NATIDE| Any other combination of UK identities (UK only)
45| 2421| NATIDE| Irish and at least one UK identity
45| 2422| NATIDE| Other identity and at least one UK identity
101| 2423| PPHHWEL| 1 person in household can speak Welsh
101| 2424| PPHHWEL| 2 people in household can speak Welsh
101| 2425| PPHHWEL| 3 people in household can speak Welsh
101| 2426| PPHHWEL| 4 people in household can speak Welsh
101| 2427| PPHHWEL| 5 people in household can speak Welsh
101| 2428| PPHHWEL| 6 or more people in household can speak Welsh
101| 2429| PPHHWEL| Total: Number of people in household who can speak Welsh
52| 2430| NUMRMS| 8 or more rooms
95| 2431| OCCHRP| 1. Managers| directors and senior officials
95| 2432| OCCHRP| 2. Professional occupations
95| 2433| OCCHRP| 3. Associate professional and technical occupations
95| 2434| OCCHRP| 4. Administrative and secretarial occupations
95| 2435| OCCHRP| 5. Skilled trades occupations
95| 2436| OCCHRP| 6. Caring| leisure and other service occupations
95| 2437| OCCHRP| 7. Sales and customer service occupations
95| 2438| OCCHRP| 8. Process| plant and machine operatives
95| 2439| OCCHRP| 9. Elementary occupations
95| 2440| OCCHRP| Total: Occupation of Household Reference Person
98| 2441| PARWRK| Total: Number of parents working
98| 2442| PARWRK| Both parents working
98| 2443| PARWRK| No parents working
98| 2444| PARWRK| One parent working
98| 2445| PARWRK| Parent not working
98| 2446| PARWRK| Parent working
55| 2447| PASHLD| Antarctica and Oceania (including Australasia)
55| 2448| PASHLD| Ireland
55| 2449| PASHLD| Central and South America
55| 2450| PASHLD| North America and the Caribbean
75| 2451| PPHALL| Ireland
75| 2452| PPHALL| Europe
75| 2453| PPHALL| The Americas and the Caribbean
75| 2454| PPHALL| Central and Western Africa
75| 2455| PPHALL| North Africa
75| 2456| PPHALL| South and Eastern Africa
75| 2457| PPHALL| Total: Passports held (total)
75| 2458| PPHALL| Antarctica and Oceania (including Australasia)
75| 2459| PPHALL| Accession countries April 2001 to March 2011
75| 2460| PPHALL| Lithuania
75| 2461| PPHALL| Other EU accession countries
75| 2462| PPHALL| Poland
75| 2463| PPHALL| Romania
75| 2464| PPHALL| Member countries in March 2001
75| 2465| PPHALL| France
75| 2466| PPHALL| Germany
75| 2467| PPHALL| Italy
75| 2468| PPHALL| Other member countries in March 2001
75| 2469| PPHALL| Portugal
75| 2470| PPHALL| Spain
75| 2471| PPHALL| Rest of Europe
75| 2472| PPHALL| Other Europe
75| 2473| PPHALL| Turkey
75| 2474| PPHALL| Central Asia
75| 2475| PPHALL| Eastern Asia
75| 2476| PPHALL| Middle East
75| 2477| PPHALL| South-East Asia
75| 2478| PPHALL| Southern Asia
75| 2479| PPHALL| Central and South America
96| 2480| RELHRP| Total: Religion of Household Reference Person
96| 2481| RELHRP| Buddhist
96| 2482| RELHRP| Christian
96| 2483| RELHRP| Hindu
96| 2484| RELHRP| Jewish
96| 2485| RELHRP| Muslim
96| 2486| RELHRP| No religion
96| 2487| RELHRP| Other religion
96| 2488| RELHRP| Religion not stated
96| 2489| RELHRP| Sikh
66| 2490| TENURE| Owned or shared ownership
66| 2491| TENURE| Owned or shared ownership (part owned and part rented)
66| 2492| TENURE| Owned with a mortgage or loan or shared ownership
66| 2493| TENURE| Private rented or living rent-free
66| 2494| TENURE| Other private rented
66| 2495| TENURE| Other private rented or living rent-free
89| 2496| WHHCOMP| Total: Welsh household composition
89| 2497| WHHCOMP| Couple household
89| 2498| WHHCOMP| No adults can speak Welsh
89| 2499| WHHCOMP| One adult can speak Welsh
89| 2500| WHHCOMP| Two or more adults can speak Welsh
89| 2501| WHHCOMP| Lone parent household
89| 2502| WHHCOMP| No adults can speak Welsh
89| 2503| WHHCOMP| One adult can speak Welsh
89| 2504| WHHCOMP| Two or more adults can speak Welsh
72| 2505| WELLANGS| Can speak and other combinations of skills in Welsh
72| 2506| WELLANGS| One or more skills in Welsh
73| 2507| YEARAUK| Born outside the UK
73| 2508| YEARAUK| Arrived before 1961
169| 2510| LPHHDC| Total: Lone-parent households with dependent children where the lone parent is aged 16 to 74
169| 2511| LPHHDC| Lone-parent households with dependent children
169| 2512| LPHHDC| In part-time employment
169| 2513| LPHHDC| In full-time employment
169| 2514| LPHHDC| Not in employment
169| 2515| LPHHDC| Male lone parent
169| 2516| LPHHDC| In part-time employment
169| 2517| LPHHDC| In full-time employment
169| 2518| LPHHDC| Not in employment
169| 2525| LPHHDC| Female lone parent
169| 2526| LPHHDC| In part-time employment
169| 2527| LPHHDC| In full-time employment
169| 2528| LPHHDC| Not in employment
106| 2529| USLANGS| Total: Ulster-Scots language skills
7| 2530| AGESST| Schoolchildren and full-time students at their term-time address
7| 2531| AGESST| Age 16 to 17
7| 2532| AGESST| Age 18 and over
48| 2533| NSSEC| L3 Higher professional occupations
48| 2534| NSSEC| L7 Intermediate occupations
48| 2535| NSSEC| L12 Semi-routine occupations
48| 2536| NSSEC| L13 Routine occupations
48| 2537| NSSEC| L14 Never worked and long-term unemployed
48| 2538| NSSEC| L16 Occupations not stated or inadequately described
49| 2539| NSSHRP| L3 Higher professional occupations
49| 2540| NSSHRP| L7 Intermediate occupations
49| 2541| NSSHRP| L12 Semi-routine occupations
49| 2542| NSSHRP| L13 Routine occupations
49| 2543| NSSHRP| L14 Never worked and long-term unemployed
49| 2544| NSSHRP| L16 Occupations not stated or inadequately described
106| 2545| USLANGS| Understands but cannot read| write or speak Ulster-Scots
106| 2546| USLANGS| Can speak but cannot read or write Ulster-Scots
106| 2547| USLANGS| Can speak and read but cannot write Ulster-Scots
106| 2548| USLANGS| Can speak| read| write and understand Ulster-Scots
106| 2549| USLANGS| Other combination of skills in Ulster-Scots
106| 2550| USLANGS| Some ability in Ulster-Scots
106| 2551| USLANGS| No ability in Ulster-Scots
107| 2552| RELSCO| Buddhist
107| 2553| RELSCO| Hindu
107| 2554| RELSCO| Jewish
107| 2555| RELSCO| Muslim
107| 2556| RELSCO| Sikh
107| 2557| RELSCO| Other religion
107| 2558| RELSCO| No religion
107| 2559| RELSCO| Religion not stated
108| 2560| RELNIR| Total: Religion (Northern Ireland)
108| 2561| RELNIR| Catholic
108| 2562| RELNIR| Presbyterian Church in Ireland
108| 2563| RELNIR| Church of Ireland
108| 2564| RELNIR| Methodist Church in Ireland
108| 2565| RELNIR| Other Christian (including Christian-related)
108| 2566| RELNIR| Other religions
108| 2567| RELNIR| No religion
109| 2568| RELBUI| Total: Religion or religion brought up in (Northern Ireland)
109| 2569| RELBUI| Catholic (including those who gave their religion or their religion brought up in as Catholic or Roman Catholic)
109| 2570| RELBUI| Protestant and other Christian (including Christian-related)
109| 2571| RELBUI| Other religions
109| 2572| RELBUI| None
110| 2573| LTCONTY| Total: Type of long-term condition
110| 2574| LTCONTY| Deafness or partial hearing loss
110| 2575| LTCONTY| Blindness or partial sight loss
110| 2576| LTCONTY| Communication difficulty
110| 2577| LTCONTY| A mobility or dexterity difficulty
110| 2578| LTCONTY| A learning| intellectual| social or behavioural difficulty
110| 2579| LTCONTY| An emotional| psychological or mental health condition
110| 2580| LTCONTY| Long-term pain or discomfort
110| 2581| LTCONTY| Shortness of breath or difficulty breathing
110| 2582| LTCONTY| Frequent periods of confusion or memory loss
110| 2583| LTCONTY| A chronic illness
110| 2584| LTCONTY| Other condition
110| 2585| LTCONTY| No condition
111| 2586| ADPACC| Total: Adaptation of accommodation
111| 2587| ADPACC| Wheelchair usage
111| 2588| ADPACC| Other physical or mobility difficulties
111| 2589| ADPACC| Visual difficulties
111| 2590| ADPACC| Hearing difficulties
111| 2591| ADPACC| Other
111| 2592| ADPACC| No adaptation to accommodation
112| 2593| COMESTR| Total: Communal establishment residents
112| 2594| COMESTR| Number of communal establishment usual residents
112| 2595| COMESTR| Communal establishment usual residents living in
112| 2596| COMESTR| Medical and care establishments
112| 2597| COMESTR| NHS/HSCT
112| 2598| COMESTR| General hospital
112| 2599| COMESTR| Mental health hospital/unit (including secure units)
112| 2600| COMESTR| Other establishment
112| 2601| COMESTR| Housing Association
112| 2602| COMESTR| Other management type
112| 2603| COMESTR| Care home with nursing
112| 2604| COMESTR| Care home without nursing
112| 2605| COMESTR| Children's home (including secure units)
112| 2606| COMESTR| Other
112| 2607| COMESTR| Education establishments
112| 2608| COMESTR| Other establishments (including education establishments)
112| 2609| COMESTR| Other establishments
18| 2611| ECOACT| Carried out voluntary work
18| 2612| ECOACT| Unemployed (excluding full-time students)
18| 2613| ECOACT| Never worked (excluding full-time students)
18| 2614| ECOACT| Long-term unemployed (excluding full-time students)
18| 2615| ECOACT| In employment (including economically active full-time students in employment)
18| 2616| ECOACT| In employment and currently working (excluding students)
43| 2617| MTTWRK| Car or van pool| shared driving
114| 2618| CRVNURA| Usual residents in households with access to a car or van
114| 2619| CRVNURA| Use public transport to travel to work
114| 2620| CRVNURA| Usual residents in households without access to a car or van
114| 2621| CRVNURA| Use public transport to travel to work
113| 2622| MTTWKS| Total: Method of travel to work or study
113| 2623| MTTWKS| Work or study mainly at or from home
113| 2624| MTTWKS| Train
113| 2625| MTTWKS| Bus| minibus or coach
113| 2626| MTTWKS| Motorcycle| scooter or moped
113| 2627| MTTWKS| Driving a car or van
113| 2628| MTTWKS| Passenger in a car or van
113| 2629| MTTWKS| Car or van pool| shared driving
113| 2630| MTTWKS| Taxi
113| 2631| MTTWKS| Bicycle
113| 2632| MTTWKS| On foot
113| 2633| MTTWKS| Other method
69| 2634| URESPOP| Primary school age and over in full-time education or aged 16-74 in employment and currently working
103| 2635| BORNIN| Born in Northern Ireland
103| 2636| BORNIN| Never resided elsewhere
103| 2637| BORNIN| Who have resided elsewhere and
103| 2638| BORNIN| Returned between 2007 and Census day
103| 2639| BORNIN| Returned between 2001 and 2006
103| 2640| BORNIN| Returned prior to 2001
103| 2641| BORNIN| Short-term residents (born outside the UK)
36| 2643| LICARG| Cohabiting (same-sex)
36| 2644| LICARG| In a registered same-sex civil partnership
69| 2645| URESPOP| Full-time students and schoolchildren aged 4 and over living away from home during term time (only including schoolchildren and students where information was provided at their home address)
28| 2646| HHDCOM| Cohabiting couple (including same-sex couples)
28| 2647| HHDCOM| No children
28| 2648| HHDCOM| One dependent child
28| 2649| HHDCOM| Two or more dependent children
28| 2650| HHDCOM| All children non-dependent
27| 2651| GHCMCAD| One adult and one or more children
27| 2652| GHCMCAD| Two adults| of whom at least one is aged 65 years and over| and no children
50| 2653| NUMAHH| 2 or more adults in household
16| 2654| DPCHDF| All dependent children in families
15| 2655| DEPCHD| One dependent child
15| 2656| DEPCHD| Two dependent children
15| 2657| DEPCHD| Three dependent children
15| 2658| DEPCHD| Four or more dependent children
15| 2659| DEPCHD| No dependent children (including households with no children)
15| 2660| DEPCHD| No dependent children (including families with no children)
20| 2661| EGRPDT| Chinese
20| 2662| EGRPDT| Irish Traveller
20| 2663| EGRPDT| Irish Traveller
20| 2664| EGRPDT| Gypsy/Romany
20| 2665| EGRPDT| Other
20| 2666| EGRPDT| Indian
20| 2667| EGRPDT| Pakistani
20| 2668| EGRPDT| Bangladeshi
20| 2669| EGRPDT| Other Asian
20| 2670| EGRPDT| Filipino
20| 2671| EGRPDT| Other Asian| Asian unspecified
20| 2672| EGRPDT| Arab
20| 2673| EGRPDT| Thai
20| 2674| EGRPDT| Malaysian
20| 2675| EGRPDT| Iranian
20| 2676| EGRPDT| Nepalese
20| 2677| EGRPDT| Other Middle East
20| 2678| EGRPDT| Japanese
20| 2679| EGRPDT| Korean
20| 2680| EGRPDT| Indonesian
20| 2681| EGRPDT| Vietnamese
20| 2682| EGRPDT| Kurdish
20| 2683| EGRPDT| Mixed Asian
20| 2684| EGRPDT| Tamil
20| 2685| EGRPDT| Burmese
20| 2686| EGRPDT| Black Caribbean
20| 2687| EGRPDT| Black African
20| 2688| EGRPDT| Black Other
20| 2689| EGRPDT| Black Other
20| 2692| EGRPDT| Black British
20| 2693| EGRPDT| Mixed Ethnic Group
20| 2694| EGRPDT| Other Mixed Ethnic
20| 2695| EGRPDT| White Asian
20| 2696| EGRPDT| White Black
20| 2697| EGRPDT| Black Asian
20| 2700| EGRPDT| Irish
20| 2701| EGRPDT| Latin/South American
20| 2702| EGRPDT| European Mixed| European unspecified
20| 2705| EGRPDT| Ulster-Scot
20| 2706| EGRPDT| English/Welsh/Scottish/Northern Irish/British
20| 2710| EGRPDT| African
20| 2712| EGRPDT| Caribbean
20| 2713| EGRPDT| Jewish
94| 2714| EGHRP| Chinese
94| 2715| EGHRP| Irish traveller
94| 2716| EGHRP| Indian
94| 2717| EGHRP| Pakistani
85| 2718| HHOLDRP| All Household Reference Persons (HRPs)
94| 2719| EGHRP| Bangladeshi
94| 2720| EGHRP| Other Asian
94| 2721| EGHRP| Black Caribbean
94| 2722| EGHRP| Black African
94| 2723| EGHRP| Black other
94| 2724| EGHRP| Mixed
12| 2726| COB| Ireland (not otherwise specified)
76| 2727| COBDET| Channel Islands and Isle of Man
76| 2728| COBDET| North America & Caribbean (including Central America)
76| 2729| COBDET| Other (persons born at sea or in the air| or with country of birth not stated)
7| 2730| AGESST| Total: Age of schoolchildren and full-time students
114| 2731| CRVNURA| Total: Usual residents in households with access to a car or van
12| 2732| COB| Republic of Ireland
12| 2733| COB| Ireland
12| 2734| COB| Island of Ireland (not otherwise specified)
12| 2735| COB| Channel Islands and Isle of Man
12| 2736| COB| EU countries
12| 2737| COB| Poland
12| 2738| COB| Lithuania
12| 2739| COB| Germany
12| 2740| COB| Slovakia
12| 2741| COB| Latvia
12| 2742| COB| Portugal
12| 2743| COB| Romania
12| 2744| COB| Hungary
12| 2745| COB| France
12| 2746| COB| Spain
12| 2747| COB| Czech Republic
12| 2748| COB| Bulgaria
12| 2749| COB| Italy
12| 2750| COB| Netherlands
12| 2751| COB| Malta
12| 2752| COB| Belgium
12| 2753| COB| Sweden
12| 2754| COB| Greece
12| 2755| COB| Gibraltar
12| 2756| COB| Austria
12| 2757| COB| Denmark
12| 2758| COB| Estonia
12| 2759| COB| Finland
12| 2760| COB| Canary Islands
12| 2761| COB| Slovenia
12| 2762| COB| Luxembourg
12| 2763| COB| Other EU Countries
12| 2764| COB| Former European countries
12| 2765| COB| Former European countries: Union of Soviet Socialist Republics (not otherwise specified)
12| 2766| COB| Czechoslovakia (not otherwise specified)
12| 2767| COB| Yugoslavia (not otherwise specified)
12| 2768| COB| Non-EU countries in Northern and Western Europe
12| 2769| COB| Switzerland
12| 2770| COB| Norway
12| 2771| COB| Iceland
12| 2772| COB| Other non-EU countries in Northern and Western Europe
12| 2773| COB| Non-EU countries in Southern and Eastern Europe
12| 2774| COB| Turkey
12| 2775| COB| Russia
12| 2776| COB| Cyprus (not otherwise specified)
12| 2777| COB| Ukraine
12| 2778| COB| Belarus
12| 2779| COB| Moldova
12| 2780| COB| Albania
12| 2781| COB| Kosovo
12| 2782| COB| Croatia
12| 2783| COB| Serbia
12| 2784| COB| Macedonia
12| 2785| COB| Bosnia and Herzegovina
12| 2786| COB| Other non-EU countries in Southern and Eastern Europe
12| 2787| COB| S?o Tom? and Pr?ncipe
12| 2788| COB| Lesotho
12| 2789| COB| Hong Kong
12| 2790| COB| East Timor
12| 2791| COB| Asia (not including the Middle East) (not otherwise specified)
12| 2792| COB| Other North America and the Caribbean
12| 2793| COB| Canada
12| 2794| COB| Caribbean
12| 2795| COB| Jamaica
12| 2796| COB| Trinidad and Tobago
12| 2797| COB| Cuba
12| 2798| COB| St. Vincent and the Grenadines
12| 2799| COB| St. Lucia
12| 2800| COB| Barbados
12| 2801| COB| Other Caribbean
12| 2802| COB| USA
12| 2803| COB| Other North America
12| 2804| COB| Bermuda
12| 2805| COB| North America (not otherwise specified)
12| 2806| COB| Other North America
12| 2807| COB| Central America
12| 2808| COB| Mexico
12| 2809| COB| Guatemala
12| 2810| COB| Belize
12| 2811| COB| Panama
12| 2812| COB| Honduras
12| 2813| COB| Other Central America
12| 2814| COB| South America
12| 2815| COB| Brazil
12| 2816| COB| Peru
12| 2817| COB| Colombia
12| 2818| COB| Argentina
12| 2819| COB| Chile
12| 2820| COB| Guyana
12| 2821| COB| Venezuela
12| 2822| COB| Ecuador
12| 2823| COB| Falkland Islands
12| 2824| COB| Bolivia
12| 2825| COB| Other South America
12| 2826| COB| Fiji
12| 2827| COB| Other Antarctica and Oceania
12| 2828| COB| North America and the Caribbean (including persons born in Central America)
12| 2829| COB| Other (persons born at sea or in the air| or with country of birth not stated)
12| 2830| COB| Non-EU countries
12| 2831| COB| Russia
12| 2832| COB| Turkey
12| 2833| COB| Other non-EU countries
115| 2834| PPHNI| Total: Passports held (Northern Ireland)
115| 2835| PPHNI| No passport held
115| 2836| PPHNI| UK only
115| 2837| PPHNI| Ireland only
115| 2838| PPHNI| UK and Ireland only
115| 2839| PPHNI| UK and other
115| 2840| PPHNI| UK and Europe
115| 2841| PPHNI| UK and EU countries
115| 2842| PPHNI| UK and France
115| 2843| PPHNI| UK and Germany
115| 2844| PPHNI| UK and Italy
115| 2845| PPHNI| UK and Netherlands
115| 2846| PPHNI| UK and Spain
115| 2847| PPHNI| UK and Poland
115| 2848| PPHNI| UK and Bulgaria
115| 2849| PPHNI| UK and Romania
115| 2850| PPHNI| UK and other EU countries
115| 2851| PPHNI| UK and Non-EU countries
115| 2852| PPHNI| UK and Northern and Western Europe
115| 2853| PPHNI| UK and Switzerland
115| 2854| PPHNI| UK and other countries in Northern and Western Europe
115| 2855| PPHNI| UK and Southern and Eastern Europe
115| 2856| PPHNI| UK and Belarus
115| 2857| PPHNI| UK and Russia
115| 2858| PPHNI| UK and Turkey
115| 2859| PPHNI| UK and other countries in Southern and Eastern Europe
115| 2860| PPHNI| UK and Africa
115| 2861| PPHNI| UK and North Africa
115| 2862| PPHNI| UK and Algeria
115| 2863| PPHNI| UK and Sudan
115| 2864| PPHNI| UK and Tunisia
115| 2865| PPHNI| UK and Egypt
115| 2866| PPHNI| UK and other North Africa
115| 2867| PPHNI| UK and Central and Western Africa
115| 2868| PPHNI| UK and Nigeria
115| 2869| PPHNI| UK and other Central and Western Africa
115| 2870| PPHNI| UK and South and Eastern Africa
115| 2871| PPHNI| UK and South Africa
115| 2872| PPHNI| UK and Zimbabwe
115| 2873| PPHNI| UK and other South and Eastern Africa
115| 2874| PPHNI| UK and Middle East and Asia
115| 2875| PPHNI| UK and Middle East
115| 2876| PPHNI| UK and Iran
115| 2877| PPHNI| UK and Israel
115| 2878| PPHNI| UK and Jordan
115| 2879| PPHNI| UK and Lebanon
115| 2880| PPHNI| UK and other Middle East
115| 2881| PPHNI| UK and Eastern Asia
115| 2882| PPHNI| UK and China
115| 2883| PPHNI| UK and Hong Kong
115| 2884| PPHNI| UK and Japan
115| 2885| PPHNI| UK and South Korea
115| 2886| PPHNI| UK and other Eastern Asia
115| 2887| PPHNI| UK and Southern Asia
115| 2888| PPHNI| UK and Bangladesh
115| 2889| PPHNI| UK and India
115| 2890| PPHNI| UK and Pakistan
115| 2891| PPHNI| UK and South-East and Central Asia
115| 2892| PPHNI| UK and Philippines
115| 2893| PPHNI| UK and Thailand
115| 2894| PPHNI| UK and other South-East and Central Asia
115| 2895| PPHNI| UK and North America and the Caribbean
115| 2896| PPHNI| UK and Canada
115| 2897| PPHNI| UK and USA
115| 2898| PPHNI| UK and the Caribbean
115| 2899| PPHNI| UK and Central America
115| 2900| PPHNI| UK and Mexico
115| 2901| PPHNI| UK and other Central America
115| 2902| PPHNI| UK and South America
115| 2903| PPHNI| UK and Brazil
115| 2904| PPHNI| UK and Chile
115| 2905| PPHNI| UK and Peru
115| 2906| PPHNI| UK and other South America
115| 2907| PPHNI| UK and Antarctica and Oceania
115| 2908| PPHNI| UK and Australia
115| 2909| PPHNI| UK and New Zealand
115| 2910| PPHNI| UK and other Antarctica and Oceania
115| 2911| PPHNI| UK and other
115| 2912| PPHNI| Ireland and other
115| 2913| PPHNI| Ireland and Europe
115| 2914| PPHNI| Ireland and EU countries
115| 2915| PPHNI| Ireland and France
115| 2916| PPHNI| Ireland and Germany
115| 2917| PPHNI| Ireland and Italy
115| 2918| PPHNI| Ireland and Spain
115| 2919| PPHNI| Ireland and Poland
115| 2920| PPHNI| Ireland and other EU countries
115| 2921| PPHNI| Ireland and non-EU countries
115| 2922| PPHNI| Ireland and Northern and Western Europe
115| 2923| PPHNI| Ireland and Southern and Eastern Europe
115| 2924| PPHNI| Ireland and Russia
115| 2925| PPHNI| Ireland and Turkey
115| 2926| PPHNI| Ireland and other countries in Southern and Eastern Europe
115| 2927| PPHNI| Ireland and Africa
115| 2928| PPHNI| Ireland and North Africa
115| 2929| PPHNI| Ireland and Central and Western Africa
115| 2930| PPHNI| Ireland and Nigeria
115| 2931| PPHNI| Ireland and other Central and Western Africa
115| 2932| PPHNI| Ireland and South and Eastern Africa
115| 2933| PPHNI| Ireland and South Africa
115| 2934| PPHNI| Ireland and other South and Eastern Africa
115| 2935| PPHNI| Ireland and Middle East and Asia
115| 2936| PPHNI| Ireland and Middle East
115| 2937| PPHNI| Ireland and Iran
115| 2938| PPHNI| Ireland and Israel
115| 2939| PPHNI| Ireland and other Middle East
115| 2940| PPHNI| Ireland and Eastern and Central Asia
115| 2941| PPHNI| Ireland and Southern Asia
115| 2942| PPHNI| Ireland and South-East Asia
115| 2943| PPHNI| Ireland and Philippines
115| 2944| PPHNI| Ireland and Thailand
115| 2945| PPHNI| Ireland and other South-East Asia
115| 2946| PPHNI| Ireland and North America and the Caribbean
115| 2947| PPHNI| Ireland and Canada
115| 2948| PPHNI| Ireland and USA
115| 2949| PPHNI| Ireland and the Caribbean
115| 2950| PPHNI| Ireland and Central America
115| 2951| PPHNI| Ireland and South America
115| 2952| PPHNI| Ireland and Antarctica and Oceania
115| 2953| PPHNI| Ireland and Australia
115| 2954| PPHNI| Ireland and New Zealand
115| 2955| PPHNI| UK| Ireland and other
115| 2956| PPHNI| UK| Ireland and Europe
115| 2957| PPHNI| UK| Ireland and EU countries
115| 2958| PPHNI| UK| Ireland and Germany
115| 2959| PPHNI| UK| Ireland and other EU countries
115| 2960| PPHNI| UK| Ireland and non-EU countries
115| 2961| PPHNI| UK| Ireland and Africa
115| 2962| PPHNI| UK| Ireland and Middle East and Asia
115| 2963| PPHNI| UK| Ireland and North America and the Caribbean
115| 2964| PPHNI| UK| Ireland and Canada
115| 2965| PPHNI| UK| Ireland and USA
115| 2966| PPHNI| UK| Ireland and the Caribbean
115| 2967| PPHNI| UK| Ireland and Central America
115| 2968| PPHNI| UK| Ireland and South America
115| 2969| PPHNI| UK| Ireland and Antarctica and Oceania
115| 2970| PPHNI| UK| Ireland and Australia
115| 2971| PPHNI| UK| Ireland and New Zealand
115| 2972| PPHNI| Other
115| 2973| PPHNI| EU/EEA countries
115| 2974| PPHNI| France
115| 2975| PPHNI| Germany
115| 2976| PPHNI| Italy
115| 2977| PPHNI| Netherlands
115| 2978| PPHNI| Spain
115| 2979| PPHNI| Poland
115| 2980| PPHNI| Austria
115| 2981| PPHNI| Belgium
115| 2982| PPHNI| Bulgaria
115| 2983| PPHNI| Czech Republic
115| 2984| PPHNI| Denmark
115| 2985| PPHNI| Estonia
115| 2986| PPHNI| Finland
115| 2987| PPHNI| Greece
115| 2988| PPHNI| Hungary
115| 2989| PPHNI| Latvia
115| 2990| PPHNI| Lithuania
115| 2991| PPHNI| Luxembourg
115| 2992| PPHNI| Malta
115| 2993| PPHNI| Portugal
115| 2994| PPHNI| Romania
115| 2995| PPHNI| Slovakia
115| 2996| PPHNI| Slovenia
115| 2997| PPHNI| Sweden
115| 2998| PPHNI| European Union (not otherwise specified)
115| 2999| PPHNI| Iceland
115| 3000| PPHNI| Norway
115| 3001| PPHNI| Total (Non-EU countries| Africa| Middle East| Asia| the Americas| Antarctica| Oceania| and British Overseas Territories)
115| 3002| PPHNI| Non-EU countries
115| 3003| PPHNI| Switzerland
115| 3004| PPHNI| Albania
115| 3005| PPHNI| Belarus
115| 3006| PPHNI| Croatia
115| 3007| PPHNI| Moldova
115| 3008| PPHNI| Russia
115| 3009| PPHNI| Serbia
115| 3010| PPHNI| Turkey
115| 3011| PPHNI| Ukraine
115| 3012| PPHNI| Cyprus (not otherwise specified)
115| 3013| PPHNI| Other non-EU countries
115| 3014| PPHNI| North Africa
115| 3015| PPHNI| Algeria
115| 3016| PPHNI| Libya
115| 3017| PPHNI| Morocco
115| 3018| PPHNI| Sudan
115| 3019| PPHNI| Tunisia
115| 3020| PPHNI| Egypt
115| 3021| PPHNI| Central and Western Africa
115| 3022| PPHNI| Nigeria
115| 3023| PPHNI| Cameroon
115| 3024| PPHNI| The Gambia
115| 3025| PPHNI| Ghana
115| 3026| PPHNI| C?te d'Ivoire
115| 3027| PPHNI| Guinea-Bissau
115| 3028| PPHNI| Other Central and Western Africa
115| 3029| PPHNI| South and Eastern Africa
115| 3030| PPHNI| Kenya
115| 3031| PPHNI| South Africa
115| 3032| PPHNI| Zimbabwe
115| 3033| PPHNI| Botswana
115| 3034| PPHNI| Malawi
115| 3035| PPHNI| Mauritius
115| 3036| PPHNI| Uganda
115| 3037| PPHNI| Tanzania
115| 3038| PPHNI| Zambia
115| 3039| PPHNI| Other South and Eastern Africa
115| 3040| PPHNI| Middle East and Asia
115| 3041| PPHNI| Middle East
115| 3042| PPHNI| Iran
115| 3043| PPHNI| Iraq
115| 3044| PPHNI| Israel
115| 3045| PPHNI| Jordan
115| 3046| PPHNI| Saudi Arabia
115| 3047| PPHNI| Syria
115| 3048| PPHNI| Other Middle East
115| 3049| PPHNI| Eastern Asia
115| 3050| PPHNI| China
115| 3051| PPHNI| Hong Kong
115| 3052| PPHNI| Japan
115| 3053| PPHNI| Taiwan (China)
115| 3054| PPHNI| South Korea
115| 3055| PPHNI| Other Eastern Asia
115| 3056| PPHNI| Southern Asia
115| 3057| PPHNI| Bangladesh
115| 3058| PPHNI| India
115| 3059| PPHNI| Pakistan
115| 3060| PPHNI| Sri Lanka
115| 3061| PPHNI| Nepal
115| 3062| PPHNI| Other Southern Asia
115| 3063| PPHNI| South-East Asia
115| 3064| PPHNI| Malaysia
115| 3065| PPHNI| Singapore
115| 3066| PPHNI| Brunei
115| 3067| PPHNI| Indonesia
115| 3068| PPHNI| Philippines
115| 3069| PPHNI| East Timor
115| 3070| PPHNI| Vietnam
115| 3071| PPHNI| Thailand
115| 3072| PPHNI| Other South-East Asia
115| 3073| PPHNI| Central Asia
115| 3074| PPHNI| North America and the Caribbean
115| 3075| PPHNI| Canada
115| 3076| PPHNI| The Caribbean
115| 3077| PPHNI| Jamaica
115| 3078| PPHNI| Cuba
115| 3079| PPHNI| St. Lucia
115| 3080| PPHNI| St. Vincent and the Grenadines
115| 3081| PPHNI| Trinidad and Tobago
115| 3082| PPHNI| Other Caribbean
115| 3083| PPHNI| USA
115| 3084| PPHNI| Central America
115| 3085| PPHNI| Honduras
115| 3086| PPHNI| Mexico
115| 3087| PPHNI| Other Central America
115| 3088| PPHNI| South America
115| 3089| PPHNI| Argentina
115| 3090| PPHNI| Brazil
115| 3091| PPHNI| Chile
115| 3092| PPHNI| Colombia
115| 3093| PPHNI| Guyana
115| 3094| PPHNI| Peru
115| 3095| PPHNI| Venezuela
115| 3096| PPHNI| Other South America
115| 3097| PPHNI| Antarctica and Oceania
115| 3098| PPHNI| Australia
115| 3099| PPHNI| New Zealand
115| 3100| PPHNI| Fiji
115| 3101| PPHNI| Other Antarctica and Oceania
115| 3102| PPHNI| British Overseas Territories
42| 3103| MLANDET| English
42| 3104| MLANDET| Chinese (not otherwise specified)
42| 3105| MLANDET| Tetum
42| 3106| MLANDET| Bengali
42| 3107| MLANDET| Panjabi (not otherwise specified)
42| 3108| MLANDET| Sign language (not otherwise specified)
42| 3109| MLANDET| Ulster-Scots
42| 3110| MLANDET| Fijian
42| 3111| MLANDET| Albanian (not otherwise specified)
42| 3112| MLANDET| Irish sign language
42| 3113| MLANDET| Indonesian Malay
42| 3114| MLANDET| Welsh/Cymraeg
42| 3115| MLANDET| Norwegian
42| 3116| MLANDET| Makaton
42| 3117| MLANDET| Philippine (not otherwise specified)
42| 3118| MLANDET| Kannada
42| 3119| MLANDET| Catalan
42| 3120| MLANDET| Hakka Chinese
42| 3121| MLANDET| Swiss German
42| 3122| MLANDET| Serbian
42| 3123| MLANDET| Kurdish (not otherwise specified)
42| 3124| MLANDET| Visayan (not otherwise specified)
42| 3125| MLANDET| Croatian
42| 3126| MLANDET| Traveller Irish
42| 3127| MLANDET| Setswana
42| 3128| MLANDET| Cebuano
42| 3129| MLANDET| Iranian
42| 3130| MLANDET| Icelandic
42| 3131| MLANDET| Creole (not otherwise specified)
42| 3132| MLANDET| Fulfulde-Pulaar
42| 3133| MLANDET| Chichewa/Chinyanja
42| 3134| MLANDET| Xhosa
57| 3135| PROENG| Main language is English
57| 3136| PROENG| Main language is not English
57| 3137| PROENG| Can speak English very well
57| 3138| PROENG| Can speak English well
57| 3139| PROENG| Cannot speak English well
57| 3140| PROENG| Cannot speak English
79| 3141| IRLANGS| Understands Irish
79| 3142| IRLANGS| Can speak Irish
79| 3143| IRLANGS| Can read Irish
79| 3144| IRLANGS| Can write Irish
106| 3148| USLANGS| Understands Ulster-Scots
106| 3149| USLANGS| Can speak Ulster-Scots
106| 3150| USLANGS| Can read Ulster-Scots
106| 3151| USLANGS| Can write Ulster-Scots
117| 3158| KNOWIR| Total: Knowledge of Irish
117| 3159| KNOWIR| Speaks but does not understand| read or write Irish
117| 3160| KNOWIR| Reads but does not understand| speak or write Irish
117| 3161| KNOWIR| Writes but does not understand| speak or read Irish
117| 3162| KNOWIR| Understands and speaks but does not read or write Irish
117| 3163| KNOWIR| Understands and reads but does not speak or write Irish
117| 3164| KNOWIR| Understands and writes but does not speak or read Irish
117| 3165| KNOWIR| Speaks and reads but does not understand or write Irish
117| 3166| KNOWIR| Speaks and writes but does not understand or read Irish
117| 3167| KNOWIR| Reads and writes but does not understand or speak Irish
117| 3168| KNOWIR| Understands| speaks and reads but does not write Irish
117| 3169| KNOWIR| Understands| speaks and writes but does not read Irish
117| 3170| KNOWIR| Understands| reads and writes but does not speak Irish
117| 3171| KNOWIR| Speaks| reads and writes but does not understand Irish
117| 3172| KNOWIR| Speaks| reads| writes and understands Irish
117| 3173| KNOWIR| No ability in Irish
117| 3174| KNOWIR| Understands but does not read| write or speak Irish
117| 3175| KNOWIR| Speaks but does not read or write Irish
117| 3176| KNOWIR| Reads but does not speak or write Irish
117| 3177| KNOWIR| Writes but does not speak or read Irish
117| 3178| KNOWIR| Speaks and reads but does not write Irish
117| 3179| KNOWIR| Reads and writes but does not speak Irish
117| 3181| KNOWIR| Other combination of skills in Irish
118| 3182| KNOWUS| Total: Knowledge of Ulster-Scots
118| 3183| KNOWUS| Understands but does not read| write or speak Ulster-Scots
118| 3184| KNOWUS| Speaks but does not understand| read or write Ulster-Scots
118| 3185| KNOWUS| Reads but does not understand| speak or write Ulster-Scots
118| 3186| KNOWUS| Writes but does not understand| speak or read Ulster-Scots
118| 3187| KNOWUS| Understands and speaks but does not read or write Ulster-Scots
118| 3188| KNOWUS| Understands and reads but does not speak or write Ulster-Scots
118| 3189| KNOWUS| Understands and writes but does not speak or read Ulster-Scots
118| 3190| KNOWUS| Speaks and reads but does not understand or write Ulster-Scots
118| 3191| KNOWUS| Speaks and writes but does not understand or read Ulster-Scots
118| 3192| KNOWUS| Reads and writes but does not understand or speak Ulster-Scots
118| 3193| KNOWUS| Understands| speaks and reads but does not write Ulster-Scots
118| 3194| KNOWUS| Understands| speaks and writes but does not read Ulster-Scots
118| 3195| KNOWUS| Understands| reads and writes but does not speak Ulster-Scots
118| 3196| KNOWUS| Speaks| reads and writes but does not understand Ulster-Scots
118| 3197| KNOWUS| Speaks| reads| writes and understands Ulster-Scots
118| 3198| KNOWUS| No ability in Ulster-Scots
118| 3199| KNOWUS| Speaks but does not read or write Ulster-Scots
118| 3200| KNOWUS| Reads but does not speak or write Ulster-Scots
118| 3201| KNOWUS| Writes but does not speak or read Ulster-Scots
118| 3202| KNOWUS| Speaks and reads but does not write Ulster-Scots
118| 3203| KNOWUS| Reads and writes but does not speak Ulster-Scots
118| 3204| KNOWUS| Other combination of skills in Ulster-Scots
108| 3205| RELNIR| Baptist
108| 3206| RELNIR| Christian
108| 3207| RELNIR| Pentecostal
108| 3208| RELNIR| Free Presbyterian
108| 3209| RELNIR| Brethren
108| 3210| RELNIR| Church of England
108| 3211| RELNIR| Protestant
108| 3212| RELNIR| Congregational Church
108| 3213| RELNIR| Evangelical
108| 3214| RELNIR| Non-denominational
108| 3215| RELNIR| Jehovah's Witness
108| 3216| RELNIR| Reformed Presbyterian
108| 3217| RELNIR| Orthodox Church
108| 3218| RELNIR| Presbyterian
108| 3219| RELNIR| Salvation Army
108| 3220| RELNIR| Church of Jesus Christ of Latter Day Saints (Mormons)
108| 3221| RELNIR| Independent Methodist
108| 3222| RELNIR| Church of Scotland
108| 3223| RELNIR| Church of the Nazarene
108| 3224| RELNIR| Religious Society of Friends (Quakers)
108| 3225| RELNIR| Non-subscribing Presbyterian
108| 3226| RELNIR| Moravian
108| 3227| RELNIR| Church of God
108| 3228| RELNIR| Methodist
108| 3229| RELNIR| Mixed Catholic/Protestant
108| 3230| RELNIR| Independent
108| 3231| RELNIR| Protestant (Mixed)
108| 3232| RELNIR| Evangelical Presbyterian Church
108| 3233| RELNIR| Seventh Day Adventist
108| 3234| RELNIR| Church
108| 3235| RELNIR| Lutheran
108| 3236| RELNIR| Unitarian
108| 3237| RELNIR| Christian Fellowship
108| 3238| RELNIR| Free Methodist
108| 3239| RELNIR| Churches of Christ
108| 3240| RELNIR| Anglican
108| 3241| RELNIR| Greek Orthodox
108| 3242| RELNIR| Russian Orthodox Church
108| 3243| RELNIR| Reformed
108| 3244| RELNIR| Apostolic Church
108| 3245| RELNIR| Interdenominational
108| 3246| RELNIR| Metropolitan Church
108| 3247| RELNIR| City Mission
108| 3248| RELNIR| Independent Evangelist
108| 3249| RELNIR| Charismatic
108| 3250| RELNIR| House Church
108| 3251| RELNIR| Church in Wales
108| 3252| RELNIR| Whitewell Metropolitan Tabernacle
108| 3253| RELNIR| Christian Fellowship Church
108| 3254| RELNIR| Christian Scientist
108| 3255| RELNIR| Free Evangelical Church
108| 3256| RELNIR| Free Church of Scotland
108| 3257| RELNIR| Eastern Orthodox Church
108| 3258| RELNIR| Dutch Reformed Church
108| 3259| RELNIR| Episcopalian
108| 3260| RELNIR| Christadelphian
108| 3261| RELNIR| Romanian Orthodox Church
108| 3262| RELNIR| United Reformed Church
108| 3263| RELNIR| Free Presbyterian Church of Scotland
108| 3264| RELNIR| Scottish Presbyterian
108| 3265| RELNIR| Faith Mission
108| 3266| RELNIR| Chinese Church
108| 3267| RELNIR| Mennonite
108| 3268| RELNIR| Free Presbyterian Church Of Ulster
108| 3269| RELNIR| Coptic Orthodox Church
108| 3270| RELNIR| Agape
108| 3271| RELNIR| British Israelite
108| 3272| RELNIR| Other Christian denominations
108| 3273| RELNIR| Muslim (Islam)
108| 3274| RELNIR| Hindu
108| 3275| RELNIR| Buddhist
108| 3276| RELNIR| Mixed religion
108| 3277| RELNIR| Jewish
108| 3278| RELNIR| Pagan
108| 3279| RELNIR| Baha'I
108| 3280| RELNIR| Spiritualist
108| 3281| RELNIR| Sikh
108| 3282| RELNIR| Wicca
108| 3283| RELNIR| Spiritual
108| 3284| RELNIR| Taoist
108| 3285| RELNIR| Scientology
108| 3286| RELNIR| Rastafarian
108| 3287| RELNIR| Druid
108| 3288| RELNIR| Chinese Religion
108| 3289| RELNIR| Believe in God
108| 3290| RELNIR| Satanism
108| 3291| RELNIR| Pantheism
108| 3292| RELNIR| Heathen
108| 3293| RELNIR| Jain
108| 3294| RELNIR| International Society for Krishna Consciousness
108| 3295| RELNIR| Own belief system
108| 3296| RELNIR| Zoroastrian
108| 3297| RELNIR| Deist
108| 3298| RELNIR| Traditional African religion
108| 3299| RELNIR| New Age
108| 3300| RELNIR| Universalist
108| 3301| RELNIR| Other religions
108| 3302| RELNIR| No religion
108| 3303| RELNIR| Jedi Knight
108| 3304| RELNIR| Atheist
108| 3305| RELNIR| Agnostic
108| 3306| RELNIR| Humanist
108| 3307| RELNIR| Heavy Metal
108| 3308| RELNIR| Free Thinker
108| 3309| RELNIR| Other
108| 3310| RELNIR| Religion not stated
119| 3311| RHRPNI| Total: Religion of Household Reference Person (Northern Ireland)
119| 3312| RHRPNI| Catholic (including those who gave their religion as Catholic or Roman Catholic)
119| 3313| RHRPNI| Presbyterian Church in Ireland
119| 3314| RHRPNI| Church of Ireland
119| 3315| RHRPNI| Methodist Church in Ireland
119| 3316| RHRPNI| Other Christian (including Christian-related)
119| 3317| RHRPNI| Other religions
119| 3318| RHRPNI| No religion
119| 3319| RHRPNI| Religion not stated
120| 3320| REBUISH| Total: Religion or religion brought up in (structure of households in Northern Ireland)
120| 3321| REBUISH| One person household
120| 3322| REBUISH| Religion or religion brought up in
120| 3323| REBUISH| All Catholic
120| 3324| REBUISH| All Protestant and other Christian (including Christian-related)
120| 3325| REBUISH| All other religions
120| 3326| REBUISH| All none
120| 3327| REBUISH| More than one person in a household
120| 3328| REBUISH| Single religion or religion brought up in
120| 3329| REBUISH| All Catholic
120| 3330| REBUISH| All Protestant and other Christian (including Christian-related)
120| 3331| REBUISH| All other religions
120| 3332| REBUISH| All none
120| 3333| REBUISH| Mixed religion or religion brought up in household
120| 3334| REBUISH| Some Catholic; No Protestant| other Christian or Christian-related; Some other religions and none
120| 3335| REBUISH| No Catholic; Some Protestant| other Christian or Christian-related; Some other religions and none
120| 3336| REBUISH| Some Catholic; Some Protestant| other Christian or Christian-related; No other religions and none
120| 3337| REBUISH| Some Catholic; Some Protestant| other Christian or Christian-related; Some other religions and none
120| 3338| REBUISH| No Catholic; No Protestant| other Christian or Christian-related; Some other religions and none
66| 3339| TENURE| Owner occupied
66| 3340| TENURE| Owned outright
66| 3341| TENURE| Owned with a mortgage or loan
66| 3342| TENURE| Housing association or charitable trust
66| 3343| TENURE| Rented from Northern Ireland Housing Executive (NIHE)
66| 3344| TENURE| Rented from housing association or charitable trust
69| 3345| URESPOP| All communal establishments
13| 3346| COMEMT| Defence (including ships)
6| 3347| AGEHRP| Age 16 to 74
6| 3350| AGEHRP| Age 16 to 64
22| 3351| ETHGRP| Scottish
22| 3352| ETHGRP| Other British
22| 3353| ETHGRP| Polish
22| 3354| ETHGRP| Asian| Asian Scottish or Asian British
22| 3355| ETHGRP| Pakistani| Pakistani Scottish or Pakistani British
22| 3356| ETHGRP| Indian| Indian Scottish or Indian British
22| 3357| ETHGRP| Bangladeshi| Bangladeshi Scottish or Bangladeshi British
22| 3358| ETHGRP| Chinese| Chinese Scottish or Chinese British
22| 3359| ETHGRP| Other Asian
22| 3360| ETHGRP| African
22| 3361| ETHGRP| African| African Scottish or African British
22| 3362| ETHGRP| Other African
22| 3363| ETHGRP| Caribbean or Black
22| 3364| ETHGRP| Caribbean| Caribbean Scottish or Caribbean British
22| 3365| ETHGRP| Black| Black Scottish or Black British
22| 3366| ETHGRP| Other Caribbean or Black
22| 3367| ETHGRP| Arab| Arab Scottish or Arab British
45| 3368| NATIDE| Other identity only (including people with a non-specific national identity such as 'citizen of the world')
12| 3369| COB| Member countries in March 2001 (including 'UK (part not specified)'| 'Channel Islands'| 'Isle of Man' and 'Ireland (part not specified)')
121| 3370| GLANGS| Total: Gaelic language skills
121| 3371| GLANGS| Can understand but cannot speak| read or write Gaelic
121| 3372| GLANGS| Can speak| read and write Gaelic
121| 3373| GLANGS| Can speak but cannot read or write Gaelic
121| 3374| GLANGS| Can speak and read but cannot write Gaelic
121| 3375| GLANGS| Can read but cannot speak or write Gaelic
121| 3376| GLANGS| Other combinations of skills in Gaelic
121| 3377| GLANGS| No skills in Gaelic
122| 3378| SCLANGS| Total: Scots language skills
122| 3379| SCLANGS| Can understand but cannot speak| read or write Scots
122| 3380| SCLANGS| Can speak| read and write Scots
122| 3381| SCLANGS| Can speak but cannot read or write Scots
122| 3382| SCLANGS| Can speak and read but cannot write Scots
122| 3383| SCLANGS| Can read but cannot speak or write Scots
122| 3384| SCLANGS| Other combinations of skills in Scots
122| 3385| SCLANGS| No skills in Scots
123| 3386| ESLANGS| Total: English and/or Scots language skills
123| 3387| ESLANGS| Can understand but cannot speak| read or write English and/or Scots
123| 3388| ESLANGS| Can speak| read and write English and/or Scots
123| 3389| ESLANGS| Can speak but cannot read or write English and/or Scots
123| 3390| ESLANGS| Can speak and read but cannot write English and/or Scots
123| 3391| ESLANGS| Can read but cannot speak or write English and/or Scots
123| 3392| ESLANGS| Other combinations of skills in English and/or Scots
123| 3393| ESLANGS| No skills in English and/or Scots
124| 3394| LANGSCO| Total: Language (Scotland)
124| 3395| LANGSCO| Can speak Gaelic
124| 3396| LANGSCO| Can speak Scots
124| 3397| LANGSCO| Language other than English used at home
124| 3398| LANGSCO| English only
124| 3399| LANGSCO| Gaelic
124| 3400| LANGSCO| Scots
124| 3401| LANGSCO| British Sign Language
124| 3402| LANGSCO| Polish
124| 3403| LANGSCO| Other
57| 3404| PROENG| Can speak English well or very well
58| 3405| PRUNCA| Provides 20 to 34 hours unpaid care a week
58| 3406| PRUNCA| Provides 35 to 49 hours unpaid care a week
31| 3407| HHSPAC| Occupied household spaces
31| 3408| HHSPAC| Unoccupied household spaces
31| 3409| HHSPAC| Second residence/holiday accommodation
31| 3410| HHSPAC| Vacant
66| 3411| TENURE| Rented
66| 3412| TENURE| Rented from council (Local Authority)
66| 3413| TENURE| Other social rented
66| 3414| TENURE| Private landlord or letting agency
66| 3415| TENURE| Other
6| 3416| AGEHRP| Total: Age of Household Reference Person
56| 3417| PCOMST| Resident (including people enumerated as sleeping rough on census night [a total of 98 in Scotland])
3| 3418| AGE| Age 18 and over
86| 3419| AGEDEP| Age 0 to 4
86| 3420| AGEDEP| All ages
10| 3421| CARVAN| All cars or vans in the area
13| 3422| COMEMT| Other (Including people enumerated as sleeping rough on census night ([a total of 98 in Scotland])
112| 3423| COMESTR| Number of communal establishment usual residents (excluding owners| staff and their partners and family members)
12| 3424| COB| Spain
18| 3425| ECOACT| 31 to 37 hours worked
18| 3426| ECOACT| 38 to 48 hours worked
18| 3427| ECOACT| 1 to 5 hours worked
18| 3428| ECOACT| 6 to 15 hours worked
18| 3429| ECOACT| Student
34| 3430| HRSWRK| 31 to 37 hours worked
34| 3431| HRSWRK| 38 to 48 hours worked
34| 3432| HRSWRK| 49 to 59 hours worked
34| 3433| HRSWRK| 60 or more hours worked
34| 3434| HRSWRK| 1 to 2 hours worked
34| 3435| HRSWRK| 3 to 5 hours worked
34| 3436| HRSWRK| 6 to 15 hours worked
105| 3437| HHSPTY| Total: Household space type
102| 3438| NUMLTHPD| 1 or more persons in household with a long-term health problem or disability
113| 3439| MTTWKS| Underground| metro| light rail or tram
69| 3440| URESPOP| All dwellings
69| 3441| URESPOP| Schoolchildren and full-time students at their term-time address
69| 3442| URESPOP| All people
69| 3443| URESPOP| All people in communal establishments
69| 3444| URESPOP| All people in households
125| 3445| NATIDNI| Total: National identity (Northern Ireland)
125| 3446| NATIDNI| British
125| 3447| NATIDNI| Irish
125| 3448| NATIDNI| Northern Irish
125| 3449| NATIDNI| British and Northern Irish
125| 3450| NATIDNI| Irish and Northern Irish
125| 3451| NATIDNI| Polish
125| 3452| NATIDNI| British| Irish and Northern Irish
125| 3453| NATIDNI| British and Irish
125| 3454| NATIDNI| English
125| 3455| NATIDNI| Scottish
125| 3456| NATIDNI| Lithuanian
125| 3457| NATIDNI| British and English
125| 3458| NATIDNI| Indian
125| 3459| NATIDNI| Slovak/Slovakian
125| 3460| NATIDNI| Portuguese
125| 3461| NATIDNI| Latvian
125| 3462| NATIDNI| Chinese
125| 3463| NATIDNI| British and Scottish
125| 3464| NATIDNI| US Citizen
125| 3465| NATIDNI| Filipino
125| 3466| NATIDNI| Welsh
125| 3467| NATIDNI| Other
125| 3468| NATIDNI| Hungarian
125| 3469| NATIDNI| Romanian
125| 3470| NATIDNI| Irish and Polish
125| 3471| NATIDNI| German
125| 3472| NATIDNI| British| English and Northern Irish
125| 3473| NATIDNI| Irish and US Citizen
125| 3474| NATIDNI| French
125| 3475| NATIDNI| Czech
125| 3476| NATIDNI| Bulgarian
125| 3477| NATIDNI| Canadian
125| 3478| NATIDNI| Spanish
125| 3479| NATIDNI| Italian
125| 3480| NATIDNI| Malaysian
125| 3481| NATIDNI| Australian
125| 3482| NATIDNI| South African
125| 3483| NATIDNI| English and Irish
125| 3484| NATIDNI| British and Welsh
125| 3485| NATIDNI| Dutch
125| 3486| NATIDNI| Irish and Lithuanian
125| 3487| NATIDNI| Russian
125| 3488| NATIDNI| British| Northern Irish and Scottish
125| 3489| NATIDNI| Irish and Other
125| 3490| NATIDNI| Pakistani
125| 3491| NATIDNI| British| English| Irish and Northern Irish
125| 3492| NATIDNI| European (not otherwise specified)
125| 3493| NATIDNI| Irish and Portuguese
125| 3494| NATIDNI| English and Northern Irish
125| 3495| NATIDNI| Nigerian (not otherwise specified)
125| 3496| NATIDNI| British and Filipino
125| 3497| NATIDNI| British and Other
125| 3498| NATIDNI| Thai
125| 3499| NATIDNI| New Zealander
125| 3500| NATIDNI| Northern Irish and Polish
125| 3501| NATIDNI| Northern Irish and Other
125| 3502| NATIDNI| Turkish
125| 3503| NATIDNI| British| Northern Irish and Ulster-Scots
125| 3504| NATIDNI| Brazilian
125| 3505| NATIDNI| British and US Citizen
125| 3506| NATIDNI| British| Irish| Northern Irish and Other
125| 3507| NATIDNI| British and Canadian
125| 3508| NATIDNI| Irish and Indian
125| 3509| NATIDNI| British and Ulster-Scots
125| 3510| NATIDNI| Irish and Australian
125| 3511| NATIDNI| British| Northern Irish and Other
125| 3512| NATIDNI| Zimbabwean
125| 3513| NATIDNI| British and Chinese
125| 3514| NATIDNI| Northern Irish and Scottish
125| 3515| NATIDNI| Northern Irish and US Citizen
125| 3516| NATIDNI| Irish and Scottish
125| 3517| NATIDNI| Swedish
125| 3518| NATIDNI| Ukrainian
125| 3519| NATIDNI| Irish and Canadian
125| 3520| NATIDNI| Bangladeshi
125| 3521| NATIDNI| British| Irish| Northern Irish and Scottish
125| 3522| NATIDNI| Greek
125| 3523| NATIDNI| Irish| Northern Irish and Other
125| 3524| NATIDNI| British and Australian
125| 3525| NATIDNI| Ulster-Scots
125| 3526| NATIDNI| Irish and Filipino
125| 3527| NATIDNI| British| Irish and Other
125| 3528| NATIDNI| British| English and Irish
125| 3529| NATIDNI| East Timorese
125| 3530| NATIDNI| Iranian
125| 3531| NATIDNI| Irish and French
125| 3532| NATIDNI| Irish and European (not otherwise specified)
125| 3533| NATIDNI| Fijian
125| 3534| NATIDNI| Asian (not otherwise specified)
125| 3535| NATIDNI| British and Polish
125| 3536| NATIDNI| Irish and Slovak/Slovakian
125| 3537| NATIDNI| Irish and Italian
125| 3538| NATIDNI| British| Irish| Northern Irish and European (not otherwise specified)
125| 3539| NATIDNI| African (not otherwise specified)
125| 3540| NATIDNI| Irish and Spanish
125| 3541| NATIDNI| British| Irish| Northern Irish and US Citizen
125| 3542| NATIDNI| Northern Irish and Canadian
125| 3543| NATIDNI| Danish
125| 3544| NATIDNI| Manx
125| 3545| NATIDNI| British and South African
125| 3546| NATIDNI| Belgian
125| 3547| NATIDNI| Irish and German
125| 3548| NATIDNI| Ghanaian/Ghanian
125| 3549| NATIDNI| Irish and Latvian
125| 3550| NATIDNI| Japanese
125| 3551| NATIDNI| Nepalese
125| 3552| NATIDNI| British| Irish and US citizen
125| 3553| NATIDNI| Estonian
125| 3554| NATIDNI| British| Northern Irish and Canadian
125| 3555| NATIDNI| Irish and South African
125| 3556| NATIDNI| Sudanese
125| 3557| NATIDNI| Northern Irish and Australian
125| 3558| NATIDNI| Irish and Chinese
125| 3559| NATIDNI| British| Northern Irish and US Citizen
125| 3560| NATIDNI| Norwegian
125| 3561| NATIDNI| Austrian
125| 3562| NATIDNI| Finnish
125| 3563| NATIDNI| English| Irish and Northern Irish
125| 3564| NATIDNI| Irish and Ulster-Scots
125| 3565| NATIDNI| English and Other
125| 3566| NATIDNI| Other combination of British/English/Irish/Northern Irish/Scottish/Welsh and Other
125| 3567| NATIDNI| Egyptian
125| 3568| NATIDNI| Jordanian
125| 3569| NATIDNI| British and French
125| 3570| NATIDNI| Swiss
125| 3571| NATIDNI| Mexican
125| 3572| NATIDNI| Hong Kong Chinese
125| 3573| NATIDNI| Taiwanese
125| 3574| NATIDNI| Algerian
125| 3575| NATIDNI| Sri Lankan
125| 3576| NATIDNI| Other combination of British/English/Irish/Northern Irish/Scottish/Welsh
125| 3577| NATIDNI| British| Irish and Scottish
125| 3578| NATIDNI| Kenyan
125| 3579| NATIDNI| Irish and Turkish
125| 3580| NATIDNI| Irish| Northern Irish and US Citizen
125| 3581| NATIDNI| British| Northern Irish and Polish
125| 3582| NATIDNI| Somali
125| 3583| NATIDNI| Irish and Zimbabwean
125| 3584| NATIDNI| Irish and Welsh
125| 3585| NATIDNI| Northern Irish and Lithuanian
125| 3586| NATIDNI| Colombian
125| 3587| NATIDNI| Northern Irish and Portuguese
125| 3588| NATIDNI| Irish and African (not otherwise specified)
125| 3589| NATIDNI| Northern Irish and French
125| 3590| NATIDNI| Irish and Hungarian
125| 3591| NATIDNI| British and Indian
125| 3592| NATIDNI| Irish and New Zealander
125| 3593| NATIDNI| British| Northern Irish and Welsh
125| 3594| NATIDNI| Saudi Arabian
125| 3595| NATIDNI| Zambian
125| 3596| NATIDNI| Irish and Brazilian
125| 3597| NATIDNI| British and New Zealander
125| 3598| NATIDNI| Irish and Nigerian (not otherwise specified)
125| 3599| NATIDNI| British| Northern Irish and European (not otherwise specified)
125| 3600| NATIDNI| Northern Irish and German
125| 3601| NATIDNI| British and Thai
125| 3602| NATIDNI| Chilean
125| 3603| NATIDNI| Irish| Northern Irish and European (not otherwise specified)
125| 3604| NATIDNI| British and German
125| 3605| NATIDNI| Indonesian
125| 3606| NATIDNI| Malawian
125| 3607| NATIDNI| Moldovian
125| 3608| NATIDNI| British| English and Other
125| 3609| NATIDNI| Bruneian
125| 3610| NATIDNI| British| English| Irish| Northern Irish and Other
125| 3611| NATIDNI| Korean (not otherwise specified)
125| 3612| NATIDNI| Irish and Dutch
125| 3613| NATIDNI| Mauritian
125| 3614| NATIDNI| Irish and Thai
125| 3615| NATIDNI| British| Irish| Northern Irish and Canadian
125| 3616| NATIDNI| Northern Irish and Welsh
125| 3617| NATIDNI| British and Pakistani
125| 3618| NATIDNI| Irish and Romanian
125| 3619| NATIDNI| British and Turkish
125| 3620| NATIDNI| Vietnamese
125| 3621| NATIDNI| Irish and Greek
125| 3622| NATIDNI| British| English| Irish| Northern Irish| Scottish and Welsh
125| 3623| NATIDNI| British and Dutch
125| 3624| NATIDNI| Jamaican
125| 3625| NATIDNI| English and Polish
125| 3626| NATIDNI| British and Spanish
125| 3627| NATIDNI| Tunisian
125| 3628| NATIDNI| British| English| Irish| Northern Irish and Scottish
125| 3629| NATIDNI| Peruvian
125| 3630| NATIDNI| Iraqi
125| 3631| NATIDNI| Argentinian
125| 3632| NATIDNI| Northern Irish and Chinese
125| 3633| NATIDNI| Northern Irish and Dutch
125| 3634| NATIDNI| Moroccan
125| 3635| NATIDNI| British| Northern Irish and Australian
125| 3636| NATIDNI| Belarusian
125| 3637| NATIDNI| Irish and Bulgarian
125| 3638| NATIDNI| Irish| Northern Irish and Scottish
125| 3639| NATIDNI| Serbian
125| 3640| NATIDNI| British| Northern Irish and South African
125| 3641| NATIDNI| British and Manx
125| 3642| NATIDNI| Singaporean
125| 3643| NATIDNI| Ugandan
125| 3644| NATIDNI| British and Russian
125| 3645| NATIDNI| Irish and East Timorese
125| 3646| NATIDNI| Northern Irish and European (not otherwise specified)
125| 3647| NATIDNI| British and Bulgarian
125| 3648| NATIDNI| British| English and Welsh
125| 3649| NATIDNI| English and Hungarian
125| 3650| NATIDNI| British and Italian
125| 3651| NATIDNI| Korean (South Korea)
125| 3652| NATIDNI| British and Lithuanian
125| 3653| NATIDNI| Maltese
125| 3654| NATIDNI| British| Irish| Northern Irish and Australian
125| 3655| NATIDNI| Cornish
125| 3656| NATIDNI| Croatian
125| 3657| NATIDNI| British| Northern Irish and New Zealander
125| 3658| NATIDNI| British| Irish| Northern Irish and Polish
125| 3659| NATIDNI| British| Scottish and Other
125| 3660| NATIDNI| Libyan
125| 3661| NATIDNI| Nigerian
125| 3662| NATIDNI| British and Nigerian (not otherwise specified)
125| 3663| NATIDNI| Albanian
125| 3664| NATIDNI| British| Irish| Northern Irish and French
125| 3665| NATIDNI| Irish and Ghanaian/Ghanian
125| 3666| NATIDNI| Irish and Manx
125| 3667| NATIDNI| Northern Irish and New Zealander
125| 3668| NATIDNI| British and Portuguese
125| 3669| NATIDNI| British and Swiss
125| 3670| NATIDNI| British| Irish| Northern Irish and Ulster-Scots
125| 3671| NATIDNI| British and Brazilian
125| 3672| NATIDNI| British and European (not otherwise specified)
125| 3673| NATIDNI| British| Northern Irish and French
125| 3674| NATIDNI| British| Northern Irish and Indian
125| 3675| NATIDNI| Israeli
125| 3676| NATIDNI| British and Romanian
125| 3677| NATIDNI| Northern Irish and South African
125| 3678| NATIDNI| British| English| Northern Irish and Other
125| 3679| NATIDNI| Cameroonian
125| 3680| NATIDNI| Irish and Czech
125| 3681| NATIDNI| British and Iranian
125| 3682| NATIDNI| Irish and Iranian
125| 3683| NATIDNI| Motswana
125| 3684| NATIDNI| British| English and Scottish
125| 3685| NATIDNI| Slovenian
125| 3686| NATIDNI| Northern Irish and Ulster-Scots
125| 3687| NATIDNI| British| Irish and Australian
125| 3688| NATIDNI| Scottish and Other
125| 3689| NATIDNI| English| Northern Irish and Other
125| 3690| NATIDNI| British| Northern Irish and Chinese
125| 3691| NATIDNI| British| Northern Irish and German
125| 3692| NATIDNI| Northern Irish and Latvian
125| 3693| NATIDNI| Lebanese
125| 3694| NATIDNI| Irish and Maltese
125| 3695| NATIDNI| British| English| Northern Irish and Scottish
125| 3696| NATIDNI| British| Northern Irish and Portuguese
125| 3697| NATIDNI| Irish and Russian
125| 3698| NATIDNI| Irish| Northern Irish and Australian
125| 3699| NATIDNI| English| Irish and Other
125| 3700| NATIDNI| Irish and Bangladeshi
125| 3701| NATIDNI| British| Irish and Canadian
125| 3702| NATIDNI| British and Egyptian
125| 3703| NATIDNI| British| Irish and French
125| 3704| NATIDNI| Guyanan/Guyanese
125| 3705| NATIDNI| British and Malaysian
125| 3706| NATIDNI| Irish and Malaysian
125| 3707| NATIDNI| Northern Irish and Spanish
125| 3708| NATIDNI| British and Zimbabwean
125| 3709| NATIDNI| Cypriot (not otherwise specified)
125| 3710| NATIDNI| Irish and Danish
125| 3711| NATIDNI| British| Irish and European (not otherwise specified)
125| 3712| NATIDNI| Irish and Fijian
125| 3713| NATIDNI| Gambian
125| 3714| NATIDNI| Irish and Japanese
125| 3715| NATIDNI| Northern Irish and Japanese
125| 3716| NATIDNI| Northern Irish and Slovak/Slovakian
125| 3717| NATIDNI| Trinidadian
125| 3718| NATIDNI| Irish and Algerian
125| 3719| NATIDNI| British and Bangladeshi
125| 3720| NATIDNI| British Overseas Territories Citizen
125| 3721| NATIDNI| British| Irish| Northern Irish and German
125| 3722| NATIDNI| British and Hong Kong Chinese
125| 3723| NATIDNI| British and Korean (South Korea)
125| 3724| NATIDNI| British| Irish and Welsh
125| 3725| NATIDNI| English and Welsh
125| 3726| NATIDNI| British| English| Northern Irish and Welsh
125| 3727| NATIDNI| Vincentian
125| 3728| NATIDNI| Irish and Asian (not otherwise specified)
125| 3729| NATIDNI| Irish and Belarusian
125| 3730| NATIDNI| British| Northern Irish| Scottish and Other
125| 3731| NATIDNI| Burmese
125| 3732| NATIDNI| Cuban
125| 3733| NATIDNI| Guinean (Guinea-Bissau)
125| 3734| NATIDNI| Northern Irish and Indian
125| 3735| NATIDNI| English and Lithuanian
125| 3736| NATIDNI| Luxembourger
125| 3737| NATIDNI| English and Scottish
125| 3738| NATIDNI| British| Northern Irish| Scottish and Welsh
125| 3739| NATIDNI| Palestinian
125| 3740| NATIDNI| English| Northern Irish and Polish
125| 3741| NATIDNI| British and Sudanese
125| 3742| NATIDNI| Tanzanian
125| 3743| NATIDNI| British| Northern Irish and Turkish
125| 3744| NATIDNI| Irish and Zambian
114| 3745| CRVNURA| Use public transport to travel to work or place of study
114| 3746| CRVNURA| Use public transport to travel to work or place of study
12| 3747| COB| Member countries prior to 2004 expansion (including 'UK (part not specified)' and 'Ireland (part not specified)')
12| 3748| COB| Accession countries 2004 onwards
15| 3749| DEPCHD| All categories: Dependent children
22| 3750| ETHGRP| Irish Traveller
20| 3751| EGRPDT| English
20| 3752| EGRPDT| Mixed Irish/Other White
20| 3753| EGRPDT| Muslim
20| 3754| EGRPDT| Northern Irish
20| 3755| EGRPDT| Roma
20| 3756| EGRPDT| Scottish
94| 3757| EGHRP| Black
115| 3758| PPHNI| Ireland and other (not UK)
115| 3759| PPHNI| EU/EEA countries (not UK or Ireland)
115| 3760| PPHNI| Other (including British Overseas Territories)
115| 3761| PPHNI| UK and other (not Ireland)
75| 3762| PPHALL| United Kingdom (including British Overseas Territories)
108| 3763| RELNIR| Catholic (including those who gave their current religion as Catholic or Roman Catholic)
106| 3764| USLANGS| Can read and write but cannot speak Ulster-Scots
106| 3765| USLANGS| Can read but cannot speak or write Ulster-Scots
106| 3766| USLANGS| Can write but cannot speak or read Ulster-Scots
66| 3767| TENURE| Rented from other (including rented from an employer of a household member or relative or friend of a household member)
66| 3768| TENURE| Rented from private landlord or letting agency
126| 3769| ETHGRSC| Total: Ethnic group (Scotland)
126| 3770| ETHGRSC| White
126| 3771| ETHGRSC| Scottish
126| 3772| ETHGRSC| Other British
126| 3773| ETHGRSC| Irish
126| 3774| ETHGRSC| Gypsy/Traveller
126| 3775| ETHGRSC| Polish
126| 3776| ETHGRSC| Other White
126| 3777| ETHGRSC| Mixed or multiple ethnic groups
126| 3778| ETHGRSC| Any mixed or multiple ethnic groups
126| 3779| ETHGRSC| Asian| Asian Scottish or Asian British
126| 3780| ETHGRSC| Pakistani| Pakistani Scottish or Pakistani British
126| 3781| ETHGRSC| Indian| Indian Scottish or Indian British
126| 3782| ETHGRSC| Bangladeshi| Bangladeshi Scottish or Bangladeshi British
126| 3783| ETHGRSC| Chinese| Chinese Scottish or Chinese British
126| 3784| ETHGRSC| Other Asian
126| 3785| ETHGRSC| African
126| 3786| ETHGRSC| African| African Scottish or African British
126| 3787| ETHGRSC| Other African
126| 3788| ETHGRSC| Caribbean or Black
126| 3789| ETHGRSC| Caribbean| Caribbean Scottish or Caribbean British
126| 3790| ETHGRSC| Black| Black Scottish or Black British
126| 3791| ETHGRSC| Other Caribbean or Black
126| 3792| ETHGRSC| Other ethnic group
126| 3793| ETHGRSC| Arab| Arab Scottish or Arab British
126| 3794| ETHGRSC| Other ethnic group
18| 3795| ECOACT| Full-time (excluding full-time students)
18| 3796| ECOACT| Self-employed (excluding full-time students)
18| 3797| ECOACT| Full-time (excluding full-time students)
18| 3798| ECOACT| Part-time (excluding full-time students)
18| 3799| ECOACT| Full-time (excluding full-time students)
18| 3800| ECOACT| Part-time (excluding full-time students)
57| 3801| PROENG| Speaks English well or very well
57| 3802| PROENG| Speaks English very well
57| 3803| PROENG| Speaks English well
57| 3811| PROENG| Does not speak English well
57| 3812| PROENG| Does not speak English at all
22| 3813| ETHGRP| Chinese
22| 3814| ETHGRP| Indian
22| 3815| ETHGRP| Pakistani
22| 3816| ETHGRP| Bangladeshi
22| 3817| ETHGRP| Asian other
22| 3818| ETHGRP| Black Caribbean
22| 3819| ETHGRP| Black African
22| 3820| ETHGRP| Black other
22| 3821| ETHGRP| Mixed
1| 3822| ACCTYP| In commercial building (including in an office building| or hotel or over a shop)
18| 3823| ECOACT| Part-time (excluding full-time students)
18| 3824| ECOACT| Long-term unemployed (where 'Year last worked' is 2009 or earlier)
105| 3825| HHSPTY| In a commercial building (including in an office building| or hotel or over a shop)
49| 3826| NSSHRP| Not classified (including L15 Full-time students)
128| 3827| VOLWOR| Total: Unpaid voluntary work
128| 3828| VOLWOR| Yes
128| 3829| VOLWOR| No
127| 3830| OCCSL| Total: Occupation (skill level)
127| 3831| OCCSL| Occupation skill level 1
127| 3832| OCCSL| Occupation skill level 2
127| 3833| OCCSL| Occupation skill level 3
127| 3834| OCCSL| Occupation skill level 4
129| 3835| NUMUR17| Total: Households
129| 3836| NUMUR17| 1 or less
129| 3837| NUMUR17| 0
129| 3838| NUMUR17| 1
129| 3839| NUMUR17| 2
129| 3840| NUMUR17| 2 or more
129| 3841| NUMUR17| 3
129| 3842| NUMUR17| 4 or more
130| 3843| NATIDC1| Total: National identity (classification 1)
130| 3844| NATIDC1| No British/Irish/Northern Irish/English/Scottish/Welsh
130| 3845| NATIDC1| At least one of British/Irish/Northern Irish/English/Scottish/Welsh
130| 3846| NATIDC1| British only
130| 3847| NATIDC1| Irish only
130| 3848| NATIDC1| Northern Irish only
130| 3849| NATIDC1| British and Northern Irish only
130| 3850| NATIDC1| Irish and Northern Irish only
130| 3851| NATIDC1| British| Irish and Northern Irish only
130| 3852| NATIDC1| British and Irish only
130| 3853| NATIDC1| English only
130| 3854| NATIDC1| Scottish only
130| 3855| NATIDC1| Welsh only
130| 3856| NATIDC1| Other British/Irish/Northern Irish/English/Scottish/Welsh only
130| 3857| NATIDC1| Other EU Member countries prior to 2004 expansion only
130| 3858| NATIDC1| Other EU Member countries prior to 2004 expansion and at least one of British/Irish/Northern Irish/English/Scottish/Welsh
130| 3859| NATIDC1| EU accession countries 2004 onwards only
130| 3860| NATIDC1| Polish only
130| 3861| NATIDC1| Lithuanian only
130| 3862| NATIDC1| Other EU Accession countries 2004 onwards only
130| 3863| NATIDC1| EU Accession countries 2004 onwards and at least one of British/Irish/Northern Irish/English/Scottish/Welsh
130| 3864| NATIDC1| Polish and at least one of British/Irish/Northern Irish/English/Scottish/Welsh
130| 3865| NATIDC1| Lithuanian and at least one of British/Irish/Northern Irish/English/Scottish/Welsh
130| 3866| NATIDC1| Other EU Accession countries 2004 onwards and at least one of British/Irish/Northern Irish/English/Scottish/Welsh
130| 3867| NATIDC1| Other only
130| 3868| NATIDC1| Other
130| 3869| NATIDC1| Other and at least one of British/Irish/Northern Irish/English/Scottish/Welsh
131| 3870| NATIDC2| Total: National identity (classification 2)
131| 3871| NATIDC2| British
131| 3872| NATIDC2| Irish
131| 3873| NATIDC2| Northern Irish
131| 3874| NATIDC2| English
131| 3875| NATIDC2| Scottish
131| 3876| NATIDC2| Welsh
131| 3877| NATIDC2| Other EU Member countries prior to 2004 expansion
131| 3878| NATIDC2| EU Accession countries 2004 onwards
131| 3879| NATIDC2| Polish
131| 3880| NATIDC2| Lithuanian
131| 3881| NATIDC2| Other EU Accession countries 2004 onwards
131| 3882| NATIDC2| Other
132| 3883| PASSC1| Total: Passports held (classification 1)
132| 3884| PASSC1| No passport
132| 3885| PASSC1| EU/EEA countries
132| 3886| PASSC1| United Kingdom
132| 3887| PASSC1| Ireland
132| 3888| PASSC1| Poland
132| 3889| PASSC1| Lithuania
132| 3890| PASSC1| Other EU/EEA (including Poland and Lithuania)
132| 3893| PASSC1| Other (non-UK and non-Ireland) and no passport
132| 3894| PASSC1| Other (non-UK and non-Ireland)
133| 3895| PASSC2| Total: Passports held (classification 2)
133| 3896| PASSC2| No passport
133| 3897| PASSC2| United Kingdom only
133| 3898| PASSC2| Ireland only
133| 3899| PASSC2| United Kingdom and Ireland only
133| 3900| PASSC2| United Kingdom and other (not Ireland)
133| 3901| PASSC2| Ireland and other (not United Kingdom)
133| 3902| PASSC2| EU/EEA (not United Kingdom or Ireland)
133| 3903| PASSC2| Other
52| 3904| NUMRMS| 1 to 2 rooms
10| 3905| CARVAN| 3 or more cars or vans in household
52| 3906| NUMRMS| 3 to 4 rooms
30| 3907| HHSIZE| 4 or more people in household
52| 3908| NUMRMS| 5 to 6 rooms
1| 3909| ACCTYP| Caravan or other mobile or temporary structure
109| 3910| RELBUI| Catholic
12| 3911| COB| Member countries prior to 2004 expansion
37| 3912| LLHPDI| Day-to-day activities limited a lot or a little
18| 3913| ECOACT| Self-employed with employees
18| 3914| ECOACT| Part-time
18| 3915| ECOACT| 15 hours or less worked
18| 3916| ECOACT| 16 to 30 hours worked
18| 3917| ECOACT| Full-time
18| 3918| ECOACT| 31 to 48 hours worked
18| 3919| ECOACT| 49 or more hours worked
18| 3920| ECOACT| Self-employed without employees
18| 3921| ECOACT| Part-time
18| 3922| ECOACT| 15 hours or less worked
18| 3923| ECOACT| 16 to 30 hours worked
18| 3924| ECOACT| Full-time
18| 3925| ECOACT| 31 to 48 hours worked
18| 3926| ECOACT| 49 or more hours worked
18| 3927| ECOACT| Full-time
18| 3928| ECOACT| Part-time
12| 3929| COB| Poland
12| 3930| COB| Lithuania
12| 3931| COB| Slovakia
12| 3932| COB| Latvia
12| 3933| COB| Romania
12| 3934| COB| Other accession countries 2004 onwards
12| 3935| COB| Europe (not otherwise specified)
12| 3936| COB| Germany
12| 3937| COB| Portugal
12| 3938| COB| Other member countries prior to 2004 expansion
6| 3941| AGEHRP| Age 16 to 24
6| 3942| AGEHRP| Age under 25
6| 3943| AGEHRP| Age 25 to 34
6| 3944| AGEHRP| Age 35 to 44
6| 3945| AGEHRP| Age 45 to 54
6| 3947| AGEHRP| Age 65 to 74
6| 3948| AGEHRP| Age 75 and over
18| 3949| ECOACT| Part-time
18| 3950| ECOACT| Full-time
134| 3951| NSSECALT| Total: NS-SeC (National Statistics Socio-economic Classification) (alternate classification)
134| 3952| NSSECALT| 1| 2 Managerial| administrative and professional occupations
134| 3953| NSSECALT| 3| 4 Intermediate occupations| small employers and own account workers
134| 3954| NSSECALT| 5| 6| 7 Technical| semi-routine| and routine occupations
134| 3955| NSSECALT| 8| 9 Never worked| long-term unemployed and full-time students
10| 3956| CARVAN| 1 or more cars or vans in household
52| 3957| NUMRMS| 7 or more rooms
3| 3958| AGE| Age 0 to 34
3| 3959| AGE| Age 10 to 11
3| 3960| AGE| Age 10 to 15
3| 3961| AGE| Age 12 to 14
3| 3962| AGE| Age 12 to 15
3| 3963| AGE| Age 16 to 19
3| 3964| AGE| Age under 20
3| 3965| AGE| Age 18 to 21
3| 3966| AGE| Age 25 to 44
3| 3967| AGE| Age 3 to 11
3| 3968| AGE| Age under 35
3| 3969| AGE| Age 35 and over
3| 3970| AGE| Age 35 to 44
3| 3971| AGE| Age 45 to 54
3| 3972| AGE| Age 45 to 74
3| 3973| AGE| Age 55 to 74
1| 3974| ACCTYP| Flat| maisonette or apartment
1| 3975| ACCTYP| House or bungalow
1| 3976| ACCTYP| Flat| maisonette| apartment| caravan or other mobile or temporary structure
3| 3977| AGE| Age 3 to 24
3| 3978| AGE| Age 4 to 9
3| 3979| AGE| Age 35 to 64
3| 3980| AGE| Age under 45
3| 3981| AGE| Age 45 and over
3| 3982| AGE| Age 55 and over
58| 3983| PRUNCA| Provides 20 or more hours unpaid care a week
12| 3984| COB| North America and the Caribbean
12| 3985| COB| Other North America and the Caribbean
135| 3986| COBCON| Total: Country of birth (condensed)
135| 3987| COBCON| Northern Ireland
135| 3988| COBCON| Other United Kingdom and Republic of Ireland
135| 3989| COBCON| Other United Kingdom
135| 3990| COBCON| Republic of Ireland
135| 3991| COBCON| Other EU countries
135| 3992| COBCON| Other
135| 3993| COBCON| Member countries prior to 2004 expansion
135| 3994| COBCON| Accession countries 2004 onwards
135| 3995| COBCON| England
135| 3996| COBCON| Scotland
135| 3997| COBCON| Wales
103| 3998| BORNIN| Born outside Northern Ireland
18| 3999| ECOACT| Never worked
18| 4000| ECOACT| Never worked
18| 4001| ECOACT| Retired
18| 4002| ECOACT| Long-term sick or disabled
18| 4003| ECOACT| Other
18| 4004| ECOACT| Student (including full-time students)
18| 4005| ECOACT| Self-employed with employees
18| 4006| ECOACT| Part-time
18| 4007| ECOACT| Full-time
18| 4008| ECOACT| Self-employed without employees
18| 4009| ECOACT| Part-time
18| 4010| ECOACT| Full-time
136| 4011| ETHGRNI| Total: Ethnic group (Northern Ireland)
136| 4012| ETHGRNI| All White
136| 4013| ETHGRNI| White
136| 4014| ETHGRNI| Irish Traveller
136| 4015| ETHGRNI| All Asian
136| 4016| ETHGRNI| Chinese
136| 4017| ETHGRNI| Indian
136| 4018| ETHGRNI| Pakistani
136| 4019| ETHGRNI| Bangladeshi
136| 4020| ETHGRNI| Other Asian
136| 4021| ETHGRNI| All Black
136| 4022| ETHGRNI| Caribbean
136| 4023| ETHGRNI| African
136| 4024| ETHGRNI| Other Black
136| 4025| ETHGRNI| Mixed
136| 4026| ETHGRNI| Other
22| 4027| ETHGRP| Asian
22| 4028| ETHGRP| Asian: Indian
22| 4029| ETHGRP| Asian: Pakistani
22| 4030| ETHGRP| Asian: Bangladeshi
22| 4031| ETHGRP| Asian: Chinese
22| 4032| ETHGRP| Asian: Other Asian
22| 4033| ETHGRP| Black
22| 4034| ETHGRP| Caribbean
22| 4035| ETHGRP| African
22| 4036| ETHGRP| Other Black
22| 4037| ETHGRP| White
90| 4038| AGEFRP| Age 50 and over
24| 4039| FAMSTA| Non-step-family (all children belong to both members of the couple)
24| 4040| FAMSTA| Step-family
24| 4041| FAMSTA| Non-step-family (all children belong to both members of the couple)
24| 4042| FAMSTA| Step-family
28| 4043| HHDCOM| Couple family
28| 4044| HHDCOM| No children
28| 4045| HHDCOM| Dependent children
28| 4046| HHDCOM| One dependent child
28| 4047| HHDCOM| Two or more dependent children
28| 4048| HHDCOM| All children non-dependent
28| 4049| HHDCOM| Male lone parent
28| 4050| HHDCOM| One dependent child
28| 4051| HHDCOM| Two or more dependent children
28| 4052| HHDCOM| All children non-dependent
28| 4053| HHDCOM| Female lone parent
28| 4054| HHDCOM| One dependent child
28| 4055| HHDCOM| Two or more dependent children
28| 4056| HHDCOM| All children non-dependent
28| 4057| HHDCOM| One dependent child
28| 4058| HHDCOM| Two or more dependent children
28| 4059| HHDCOM| Other
6| 4060| AGEHRP| Age 45 to 64
137| 4061| TENALT| Total: Tenure (alternative classification)
137| 4062| TENALT| Living with parent(s)
137| 4063| TENALT| Communal establishment
137| 4064| TENALT| All-student group household
137| 4065| TENALT| Owner occupied
137| 4066| TENALT| Rented from NIHE
137| 4067| TENALT| Rented from housing association or charitable trust
137| 4068| TENALT| Private rented
137| 4069| TENALT| Student living alone
137| 4070| TENALT| Owner occupied
137| 4071| TENALT| Rented from NIHE
137| 4072| TENALT| Rented from housing association or charitable trust
137| 4073| TENALT| Private rented
137| 4074| TENALT| Other household type
137| 4075| TENALT| Owner occupied
137| 4076| TENALT| Rented from NIHE
137| 4077| TENALT| Rented from housing association or charitable trust
137| 4078| TENALT| Private rented
100| 4079| HHSFTATT| Households with two or more students away during term-time
100| 4080| HHSFTATT| All aged 4 to 17
100| 4081| HHSFTATT| All aged 18 and over
100| 4082| HHSFTATT| Combination of aged 4 to 17 and 18 and over
182| 4083| MNLANNI| Polish
182| 4084| MNLANNI| Lithuanian
182| 4085| MNLANNI| Irish (Gaelic)
182| 4086| MNLANNI| Slovak
182| 4087| MNLANNI| Chinese
182| 4088| MNLANNI| Tagalog/Filipino
182| 4089| MNLANNI| Latvian
182| 4090| MNLANNI| Russian
182| 4091| MNLANNI| Malayalam
182| 4092| MNLANNI| Hungarian
182| 4093| MNLANNI| Other
97| 4094| MAINLAN| English
108| 4095| RELNIR| Other religions and no religion
108| 4096| RELNIR| Other religions| no religion and religion not stated
39| 4097| MACPST| Married or in a registered same-sex civil partnership
39| 4098| MACPST| Not married or in a registered same-sex civil partnership
39| 4099| MACPST| Not single| married or in a registered same-sex civil partnership
108| 4114| RELNIR| Protestant and other Christian
109| 4115| RELBUI| Other religions and none
56| 4116| PCOMST| Resident staff and families
118| 4117| KNOWUS| Some ability in Ulster-Scots
117| 4118| KNOWIR| Some ability in Irish
140| 4119| FOROCC| Total: Former occupation
140| 4120| FOROCC| 1. Managers| directors and senior officials
140| 4121| FOROCC| 2. Professional occupations
140| 4122| FOROCC| 3. Associate professional and technical occupations
140| 4123| FOROCC| 4. Administrative and secretarial occupations
140| 4124| FOROCC| 5. Skilled trades occupations
140| 4125| FOROCC| 6. Caring| leisure and other service occupations
140| 4126| FOROCC| 7. Sales and customer service occupations
140| 4127| FOROCC| 8. Process| plant and machine operatives
140| 4128| FOROCC| 9. Elementary occupations
140| 4129| FOROCC| Never worked
141| 4130| FORIND| Total: Former industry
141| 4131| FORIND| A Agriculture| forestry and fishing
141| 4132| FORIND| B Mining and quarrying
141| 4133| FORIND| C Manufacturing
141| 4134| FORIND| C10-12 Manufacturing: Food| beverages and tobacco
141| 4135| FORIND| C13-15 Manufacturing: Textiles| wearing apparel and leather and related products
141| 4136| FORIND| C16|17 Manufacturing: Wood| paper and paper products
141| 4137| FORIND| C19-22 Manufacturing: Chemicals| chemical products| rubber and plastic
141| 4138| FORIND| C23-25 Manufacturing: Low tech
141| 4139| FORIND| C26-30 Manufacturing: High tech
141| 4140| FORIND| C18| 31| 32 Manufacturing: Other
141| 4141| FORIND| D Electricity| gas| steam and air conditioning supply
141| 4142| FORIND| E Water supply| sewerage| waste management and remediation activities
141| 4143| FORIND| F Construction
141| 4144| FORIND| G Wholesale and retail trade; repair of motor vehicles and motor cycles
141| 4145| FORIND| H Transport and storage
141| 4146| FORIND| I Accommodation and food service activities
141| 4147| FORIND| J Information and communication
141| 4148| FORIND| K Financial and insurance activities
141| 4149| FORIND| L Real estate activities
141| 4150| FORIND| M Professional| scientific and technical activities
141| 4151| FORIND| N Administrative and support service activities
141| 4152| FORIND| O Public administration and defence; compulsory social security
141| 4153| FORIND| P Education
141| 4154| FORIND| Q Human health and social work activities
141| 4155| FORIND| R| S Arts| entertainment and recreation; other service activities
141| 4156| FORIND| T Activities of households as employers; undifferentiated goods - and services - producing activities of households for own use
141| 4157| FORIND| U Activities of extraterritorial organisations and bodies
141| 4158| FORIND| Never worked
103| 4159| BORNIN| Total: Country of birth (alternative classification)
53| 4160| OCCUP| Never worked or occupation not coded
35| 4161| INDUST| Not in employment
142| 4162| ACTLWK| Total: Activity the week before the census
142| 4163| ACTLWK| Working
142| 4164| ACTLWK| Not working
143| 4165| APPSOCG| Total: Approximated social grade
143| 4166| APPSOCG| AB Higher and intermediate managerial/administrative/professional occupations
143| 4167| APPSOCG| C1 Supervisory| clerical and junior managerial/administrative/professional occupations
143| 4168| APPSOCG| C2 Skilled manual occupations
143| 4169| APPSOCG| DE Semi-skilled and unskilled manual occupations; unemployed and lowest grade occupations
144| 4170| DISTWRK| All categories: Distance travelled to work
144| 4171| DISTWRK| Less than 2km
144| 4172| DISTWRK| 2km to less than 5km
144| 4173| DISTWRK| 5km to less than 10km
144| 4174| DISTWRK| 10km to less than 20km
144| 4175| DISTWRK| 20km to less than 30km
144| 4176| DISTWRK| 30km to less than 40km
144| 4177| DISTWRK| 40km to less than 60km
144| 4178| DISTWRK| 60km and over
144| 4179| DISTWRK| Work mainly at or from home
144| 4180| DISTWRK| No fixed place
144| 4181| DISTWRK| Not in employment
144| 4182| DISTWRK| Total distance (km)
144| 4183| DISTWRK| Average distance (km)
145| 4184| MTW2001| Total: Means of travel to work (2001 specifications)
145| 4185| MTW2001| Work mainly at or from home
145| 4186| MTW2001| Underground| metro| light rail or tram
145| 4187| MTW2001| Train
145| 4188| MTW2001| Bus| minibus or coach
145| 4189| MTW2001| Taxi
145| 4190| MTW2001| Motorcycle| scooter or moped
145| 4191| MTW2001| Driving a car or van
145| 4192| MTW2001| Passenger in a car or van
145| 4193| MTW2001| Bicycle
145| 4194| MTW2001| On foot
145| 4195| MTW2001| Other method of travel to work
145| 4196| MTW2001| Not in employment
12| 4197| COB| Portugal
72| 4198| WELLANGS| Can read but cannot speak or write Welsh
72| 4199| WELLANGS| Can read and write but cannot speak Welsh
72| 4200| WELLANGS| Can write but cannot speak or read Welsh
35| 4201| INDUST| A| B| D| E Agriculture| energy and water
33| 4203| HIQUAL| Apprenticeships and other qualifications
145| 4204| MTW2001| Train| underground| metro| light rail| tram| bus| minibus or coach
145| 4205| MTW2001| All other methods of travel to work
174| 4206| DAYPOP| Workplace population
144| 4207| DISTWRK| 10km to less than 30km
144| 4208| DISTWRK| 30km to less than 60km
144| 4209| DISTWRK| Less than 5km
34| 4210| HRSWRK| Not in employment
77| 4211| OGRPMIN| Not in employment
146| 4212| HRPAP| Total: Household Reference Persons and associated persons in household
146| 4213| HRPAP| Associated persons in household
146| 4214| HRPAP| Household reference person
69| 4216| URESPOP| Member of the Armed Forces
69| 4217| URESPOP| All HRPs who are members of the Armed Forces and are usual residents and all associated persons in households with members of the Armed Forces who are also usual residents
69| 4218| URESPOP| All associated people aged 16 and over who are usual residents in households with members of the Armed Forces who are also usual residents
69| 4219| URESPOP| Member of the Foreign Armed Forces
69| 4220| URESPOP| All household reference persons aged 16 to 64 in households
1| 4221| ACCTYP| In a commercial building
1| 4222| ACCTYP| Purpose-built block of flats or tenement
1| 4223| ACCTYP| Part of a converted or shared house (including bed-sits)
12| 4224| COB| North Africa (including 'Africa (not otherwise specified)')
12| 4225| COB| Republic of Ireland (including 'Ireland (not otherwise specified)' for England and Wales)
12| 4226| COB| Other EU countries (including 'Ireland (not otherwise specified)' for Scotland and Northern Ireland| and 'Cyprus (not otherwise specified)' for England and Wales)
12| 4227| COB| Other rest of Europe (including 'Cyprus (not otherwise specified)' for Scotland and Northern Ireland)
22| 4228| ETHGRP| Gypsy/Traveller/Irish Traveller
33| 4230| HIQUAL| Apprenticeship (not applicable to Scotland)
33| 4231| HIQUAL| Other qualifications (not applicable to Scotland. This category consists of other vocational/work-related qualifications and non-UK/foreign qualifications)
68| 4232| UNIT| Kilometres
68| 4235| UNIT| Years
69| 4236| URESPOP| All household reference persons in households
13| 4237| COMEMT| Housing Association
148| 4238| COMESTNI| Total: Communal establishment management and type (Northern Ireland)
148| 4239| COMESTNI| Medical and care establishments
148| 4240| COMESTNI| HSCT
148| 4241| COMESTNI| Housing Association
148| 4242| COMESTNI| Other management type
148| 4243| COMESTNI| Care home with nursing
148| 4244| COMESTNI| Care home without nursing
148| 4245| COMESTNI| Other
148| 4246| COMESTNI| Other establishments
103| 4247| BORNIN| Born outside Northern Ireland| Republic of Ireland and Scotland
103| 4248| BORNIN| Born in Republic of Ireland
103| 4249| BORNIN| Born in Scotland
149| 4250| DEPCHILDHH| All categories: Dependent children in household
149| 4251| DEPCHILDHH| No dependent children in household
149| 4252| DEPCHILDHH| One or more dependent children in household
149| 4253| DEPCHILDHH| Youngest aged 0 to 4
149| 4254| DEPCHILDHH| Youngest aged 5 to 9
149| 4255| DEPCHILDHH| Youngest aged 10 to 15
149| 4256| DEPCHILDHH| Youngest aged 16 to 18
16| 4257| DPCHDF| Aged 5 to 7
16| 4258| DPCHDF| Aged 8 to 9
16| 4259| DPCHDF| Aged 10 to 11
16| 4260| DPCHDF| Aged 12 to 15
16| 4261| DPCHDF| Aged 16 to 18
16| 4262| DPCHDF| Youngest aged 5 to 7
16| 4263| DPCHDF| Youngest aged 8 to 9
16| 4264| DPCHDF| Youngest aged 10 to 11
16| 4265| DPCHDF| Youngest aged 12 to 15
16| 4266| DPCHDF| Youngest aged 16 to 18
16| 4267| DPCHDF| Youngest aged 5 to 7
16| 4268| DPCHDF| Youngest aged 8 to 9
16| 4269| DPCHDF| Youngest aged 10 to 11
16| 4270| DPCHDF| Youngest aged 12 to 15
16| 4271| DPCHDF| Youngest aged 16 to 18
26| 4272| GENHEA| Fair| bad or very bad health
48| 4273| NSSEC| Never worked| long term unemployed and full-time students
119| 4274| RHRPNI| Protestant and other Christian (including Christian-related)
119| 4275| RHRPNI| Catholic
119| 4276| RHRPNI| Other religions| no religion and religion not stated
6| 4277| AGEHRP| Age under 45
132| 4278| PASSC1| Other
132| 4279| PASSC1| Other EU/EEA (not including Poland and Lithuania)
97| 4280| MAINLAN| Not English
119| 4281| RHRPNI| Catholic
150| 4282| REBUIHRP| Total: Religion or religion brought up in of Household Reference Person (Northern Ireland)
150| 4283| REBUIHRP| Catholic
150| 4284| REBUIHRP| Protestant and other Christian (including Christian-related)
150| 4285| REBUIHRP| Other religions and none
151| 4286| COBHRP| Total: Country of birth of Household Reference Person (Northern Ireland)
151| 4287| COBHRP| Born in Northern Ireland
151| 4288| COBHRP| Born outside Northern Ireland
152| 4289| NSHRPALT| Total: NS-SeC (National Statistics Socio-economic Classification) of Household Reference Person (alternate classification)
152| 4290| NSHRPALT| 1| 2 Managerial| administrative and professional occupations
152| 4291| NSHRPALT| 3| 4 Intermediate occupations and small employers
152| 4292| NSHRPALT| 5| 6| 7 Routine and manual occupations
152| 4293| NSHRPALT| 8| 9 Never worked| long-term unemployed and full-time students
19| 4294| ECPHRP| In employment
19| 4295| ECPHRP| Not in employment
6| 4296| AGEHRP| Age under 20
6| 4297| AGEHRP| Age 20 to 24
6| 4298| AGEHRP| Age 25 to 29
6| 4299| AGEHRP| Age 30 to 34
6| 4300| AGEHRP| Age 35 to 39
6| 4301| AGEHRP| Age 40 to 44
6| 4302| AGEHRP| Age 45 to 49
6| 4303| AGEHRP| Age 50 to 54
6| 4304| AGEHRP| Age 55 to 59
6| 4305| AGEHRP| Age 60 to 64
6| 4306| AGEHRP| Age 65 to 69
6| 4307| AGEHRP| Age 70 to 74
6| 4308| AGEHRP| Age 75 to 79
6| 4309| AGEHRP| Age 80 to 84
6| 4310| AGEHRP| Age 85 to 89
6| 4311| AGEHRP| Age 90 and over
168| 4312| EGHRPNI| Total: Ethnic group of Household Reference Person (Northern Ireland)
168| 4313| EGHRPNI| White
168| 4314| EGHRPNI| White
168| 4315| EGHRPNI| Irish Traveller
168| 4316| EGHRPNI| Asian
168| 4317| EGHRPNI| Chinese
168| 4318| EGHRPNI| Indian
168| 4319| EGHRPNI| Pakistani
168| 4320| EGHRPNI| Bangladeshi
168| 4321| EGHRPNI| Other Asian
168| 4322| EGHRPNI| Black
168| 4323| EGHRPNI| Caribbean
168| 4324| EGHRPNI| African
168| 4325| EGHRPNI| Other Black
168| 4326| EGHRPNI| Mixed
168| 4327| EGHRPNI| Other
16| 4328| DPCHDF| No children
16| 4329| DPCHDF| With dependent children
16| 4330| DPCHDF| All children non-dependent
24| 4331| FAMSTA| No children or non-step-family (all children belong to both members of the couple)
56| 4332| PCOMST| Family member of staff or owner
16| 4333| DPCHDF| Dependent children in family
16| 4334| DPCHDF| Youngest aged 0 to 4
16| 4335| DPCHDF| Youngest aged 5 to 7
16| 4336| DPCHDF| Youngest aged 8 to 9
16| 4337| DPCHDF| Youngest aged 10 to 11
16| 4338| DPCHDF| Youngest aged 12 to 15
16| 4339| DPCHDF| Youngest aged 16 to 18
154| 4341| COMTY| Total: Communal establishment type
154| 4342| COMTY| Medical and care establishments
154| 4343| COMTY| Hospitals
154| 4344| COMTY| Adult care homes
154| 4345| COMTY| Children's homes (including secure units)
154| 4346| COMTY| Education establishments
154| 4347| COMTY| Halls of residence and student accommodation
154| 4348| COMTY| Schools and other education establishments
154| 4349| COMTY| Defence establishments
154| 4350| COMTY| Prison service establishments
154| 4351| COMTY| Hotels and holiday accommodation
154| 4352| COMTY| Hostels for homeless or temporary shelter
154| 4353| COMTY| Other establishments (including establishment types not elsewhere specified and people enumerated as sleeping rough on census night [a total of 98 in Scotland])
56| 4354| PCOMST| Staff or owner| or family member or partner of staff or owner
16| 4355| DPCHDF| Two or more dependent children in family
16| 4356| DPCHDF| Youngest aged 0 to 4
16| 4357| DPCHDF| Youngest aged 5 to 11
16| 4358| DPCHDF| Youngest aged 12 to 18
24| 4359| FAMSTA| No children or non-step-family (all children belong to both members of the couple)
16| 4360| DPCHDF| Youngest aged 5 to 11
16| 4361| DPCHDF| Youngest aged 12 to 18
24| 4362| FAMSTA| No children or non-step-family (all children belong to both members of the couple)
24| 4363| FAMSTA| Couple family: Step-family
6| 4364| AGEHRP| Age 35 to 49
6| 4365| AGEHRP| Age 50 to 64
6| 4366| AGEHRP| Age 75 to 84
6| 4367| AGEHRP| Age 85 and over
3| 4368| AGE| Age 95 and over
16| 4369| DPCHDF| Aged 5 to 9
16| 4370| DPCHDF| Youngest aged 5 to 9
16| 4371| DPCHDF| Youngest aged 5 to 9
7| 4372| AGESST| All schoolchildren or students aged 4 to 17
7| 4373| AGESST| Combination of schoolchildren or students aged 4 to 17 and 18 and over
7| 4374| AGESST| All schoolchildren or students aged 18 and over
110| 4375| LTCONTY| One or more conditions
110| 4376| LTCONTY| Learning disability
110| 4377| LTCONTY| Learning difficulty
110| 4378| LTCONTY| Developmental disorder
110| 4379| LTCONTY| Physical disability
110| 4380| LTCONTY| Mental health condition
12| 4382| COB| Non-EU countries
24| 4383| FAMSTA| Member of couple
24| 4384| FAMSTA| Child of couple
24| 4385| FAMSTA| Parent
24| 4386| FAMSTA| Child of parent
58| 4387| PRUNCA| Provides 35 or more hours unpaid care a week
155| 4388| LANENG| Total: Language other than English used at home
155| 4389| LANENG| English only
155| 4390| LANENG| Gaelic
155| 4391| LANENG| Scots
155| 4392| LANENG| British Sign Language
155| 4393| LANENG| Polish
155| 4394| LANENG| Other
66| 4395| TENURE| Private landlord or letting agency
66| 4396| TENURE| Other private rented or living rent-free
7| 4397| AGESST| All schoolchildren or students aged 4 and over
69| 4398| URESPOP| All people in families
18| 4399| ECOACT| Part-time (including full-time students)
18| 4400| ECOACT| Full-time (including full-time students)
18| 4401| ECOACT| Part-time (including full-time students)
18| 4402| ECOACT| Full-time (including full-time students)
156| 4403| LIVARALT| Total: Living arrangements (alternative classification)
156| 4404| LIVARALT| Living with parent(s)
156| 4405| LIVARALT| One person household
156| 4406| LIVARALT| Living as couple
156| 4407| LIVARALT| Living as a lone parent
156| 4408| LIVARALT| Other households
156| 4409| LIVARALT| Living in an educational establishment
126| 4410| ETHGRSC| Other (including 'White: Gypsy/Traveller'| 'White: Polish'| and 'White: Other White')
18| 4411| ECOACT| Other (including 'Looking after home or family' and 'Long-term sick or disabled')
69| 4412| URESPOP| All people in households or educational establishments
157| 4413| NATIDSC| Total: National identity (Scotland)
157| 4414| NATIDSC| Scottish identity only
157| 4415| NATIDSC| British identity only
157| 4416| NATIDSC| Scottish and British identities only
157| 4417| NATIDSC| Scottish and any other identities
157| 4418| NATIDSC| English identity only
157| 4419| NATIDSC| Any other combination of UK identities (UK only)
157| 4420| NATIDSC| Other identity only (including people with a non-specific national identity such as 'Citizen of the World')
157| 4421| NATIDSC| Other identity and at least one UK identity
3| 4422| AGE| Age 20 to 34
18| 4423| ECOACT| Economically active: Employee (including full-time students)
18| 4424| ECOACT| Economically active: Self-employed (including full-time students)
155| 4425| LANENG| Other (including British Sign Language| Gaelic and other languages)
123| 4427| ESLANGS| Other combinations of skills in English and/or Scots (including 'Can read but cannot speak or write English and/or Scots')
12| 4428| COB| Antarctica| Oceania and Other
28| 4429| HHDCOM| With dependent children
28| 4430| HHDCOM| With dependent children
28| 4431| HHDCOM| With dependent children
28| 4432| HHDCOM| With dependent children
6| 4433| AGEHRP| Age 25 to 49
91| 4434| AGEYDC| Age 10 to 11
91| 4435| AGEYDC| Age 5 to 7
91| 4436| AGEYDC| Age 8 to 9
158| 4437| EGHRPSC| Total: Ethnic group of Household Reference Person (Scotland)
158| 4438| EGHRPSC| White
158| 4439| EGHRPSC| Scottish
158| 4440| EGHRPSC| Other British
158| 4441| EGHRPSC| Irish
158| 4442| EGHRPSC| Gypsy/Traveller
158| 4443| EGHRPSC| Polish
158| 4444| EGHRPSC| Other White
158| 4445| EGHRPSC| Mixed or multiple ethnic groups
158| 4446| EGHRPSC| Asian| Asian Scottish or Asian British
158| 4447| EGHRPSC| Pakistani| Pakistani Scottish or Pakistani British
158| 4448| EGHRPSC| Indian| Indian Scottish or Indian British
158| 4449| EGHRPSC| Bangladeshi| Bangladeshi Scottish or Bangladeshi British
158| 4450| EGHRPSC| Chinese| Chinese Scottish or Chinese British
158| 4451| EGHRPSC| Other Asian
158| 4452| EGHRPSC| African
158| 4453| EGHRPSC| African| African Scottish or African British
158| 4454| EGHRPSC| Other African
158| 4455| EGHRPSC| Caribbean or Black
158| 4456| EGHRPSC| Caribbean| Caribbean Scottish or Caribbean British
158| 4457| EGHRPSC| Black| Black Scottish or Black British
158| 4458| EGHRPSC| Other Caribbean or Black
158| 4459| EGHRPSC| Other ethnic groups
158| 4460| EGHRPSC| Arab| Arab Scottish or Arab British
158| 4461| EGHRPSC| Other ethnic group
158| 4462| EGHRPSC| Other (including 'White: Gypsy/Traveller'| 'White: Polish' and 'White: Other White')
43| 4463| MTTWRK| Train or underground| metro| light rail or tram
43| 4464| MTTWRK| All other methods of travel to work (including taxi or minicab| motorcycle| scooter or moped and other methods of travel not elsewhere specified)
159| 4465| MTTSTD| Total: Method of travel to place of study
159| 4466| MTTSTD| Study mainly at home
159| 4467| MTTSTD| Underground| metro| light rail or tram
159| 4468| MTTSTD| Train
159| 4469| MTTSTD| Bus| minibus or coach
159| 4470| MTTSTD| Taxi or minicab
159| 4471| MTTSTD| Driving a car or van
159| 4472| MTTSTD| Passenger in a car or van
159| 4473| MTTSTD| Motorcycle| scooter or moped
159| 4474| MTTSTD| Bicycle
159| 4475| MTTSTD| On foot
159| 4476| MTTSTD| Other
113| 4477| MTTWKS| Train or underground| metro| light rail or tram
113| 4478| MTTWKS| All other methods of travel to work (including taxi or minicab| motorcycle| scooter or moped and other methods of travel not elsewhere specified)
74| 4479| YEARLW| Last worked in 2010-2011
74| 4480| YEARLW| Last worked in 2008-2009
74| 4481| YEARLW| Last worked in 2006-2007
18| 4482| ECOACT| In employment the week before the census (excluding full-time students)
69| 4483| URESPOP| All people studying the week before the census
69| 4484| URESPOP| All people aged 16 and over studying or aged 16 to 74 in employment the week before the census
3| 4485| AGE| Age 4 to 11
18| 4486| ECOACT| Part-time (including full-time students)
18| 4487| ECOACT| Full-time (including full-time students)
18| 4488| ECOACT| Part-time (including full-time students)
18| 4489| ECOACT| Full-time (including full-time students)
18| 4490| ECOACT| Employee (excluding full-time students)
18| 4491| ECOACT| Part-time (excluding full-time students)
18| 4492| ECOACT| Full-time (excluding full-time students)
18| 4493| ECOACT| Self-employed (excluding full-time students)
18| 4494| ECOACT| Part-time (excluding full-time students)
18| 4495| ECOACT| Full-time (excluding full-time students)
66| 4496| TENURE| Rented or living rent-free
160| 4497| URESPLC| Total: Place of usual residence
160| 4498| URESPLC| Lives in the workplace zone
160| 4499| URESPLC| Lives outside the workplace zone but within the middle layer super output area
160| 4500| URESPLC| Lives outside the middle layer super output area but within the local authority
160| 4501| URESPLC| Lives outside the local authority but within the region
160| 4502| URESPLC| Lives outside the region but within England and Wales
18| 4503| ECOACT| In employment in the area the week before the census
150| 4504| REBUIHRP| Other religions
150| 4505| REBUIHRP| None
150| 4506| REBUIHRP| Catholic (including those who gave their religion or their religion brought up in as Catholic or Roman Catholic)
19| 4507| ECPHRP| Student
18| 4508| ECOACT| 15 hours or less worked
69| 4509| URESPOP| All people aged 4 and over studying or aged 16 to 74 in employment the week before the census
18| 4510| ECOACT| 1 to 5 hours worked
18| 4511| ECOACT| 6 to 15 hours worked
18| 4512| ECOACT| 16 to 30 hours worked
18| 4513| ECOACT| 31 to 48 hours worked
18| 4515| ECOACT| 31 to 37 hours worked
18| 4516| ECOACT| 38 to 48 hours worked
18| 4517| ECOACT| 49 or more hours worked
141| 4518| FORIND| A| B| D| E Agriculture| energy and water
141| 4519| FORIND| R| S| T| U Other
161| 4520| CARUNP| All categories: Unpaid carers
161| 4521| CARUNP| No unpaid carers in household
161| 4522| CARUNP| One unpaid carer in household
161| 4523| CARUNP| Working part-time
58| 4524| PRUNCA| Provides 1 to 34 hours unpaid care a week
161| 4525| CARUNP| Working full-time
161| 4526| CARUNP| Unemployed
161| 4527| CARUNP| Economically active full-time student
161| 4528| CARUNP| Economically inactive
161| 4529| CARUNP| Two or more unpaid carers in household
141| 4530| FORIND| G| I Distribution| hotels and restaurants
141| 4531| FORIND| H| J Transport and communication
141| 4532| FORIND| K| L| M| N Financial| real estate| professional and administrative activities
141| 4533| FORIND| O| P| Q Public administration| education and health
49| 4534| NSSHRP| Other (including '8. Never worked and long-term unemployed' and 'Not classified: L15 Full-time students')
69| 4535| URESPOP| All households with schoolchildren or full-time students aged 4 and over living away during term-time
18| 4536| ECOACT| Not in employment the week before the census
162| 4537| STUACC| Total: Student accommodation
162| 4538| STUACC| Living with parents
162| 4539| STUACC| Living in a communal establishment
162| 4540| STUACC| Educational establishments
162| 4541| STUACC| Other
162| 4542| STUACC| Living in all-student household
162| 4543| STUACC| Student living alone
162| 4544| STUACC| Other household type
69| 4545| URESPOP| All usual residents who are either in employment in the area| or not in employment but live in the area
69| 4546| URESPOP| All usual residents in employment in the area the week before the census
148| 4547| COMESTNI| General hospital
148| 4548| COMESTNI| Mental health hospital/unit (including secure units)
148| 4549| COMESTNI| Other hospital
148| 4550| COMESTNI| Home or hostel
148| 4551| COMESTNI| Sheltered housing only
148| 4552| COMESTNI| Other
148| 4553| COMESTNI| Care home with nursing
148| 4554| COMESTNI| Care home without nursing
148| 4555| COMESTNI| Children's home (including secure units)
148| 4556| COMESTNI| Mental health hospital/unit (including secure units)
148| 4557| COMESTNI| Other hospital
148| 4558| COMESTNI| Other establishments
148| 4559| COMESTNI| Defence
148| 4560| COMESTNI| Prison service
148| 4561| COMESTNI| Approved premises (probation/bail hostel)
148| 4562| COMESTNI| Detention centres and other detention
148| 4563| COMESTNI| Education
148| 4564| COMESTNI| Hotel
148| 4565| COMESTNI| Hotel| guest house| B&B or youth hostel
148| 4566| COMESTNI| Hostel or temporary shelter for the homeless
148| 4567| COMESTNI| Other travel or temporary accommodation
148| 4568| COMESTNI| Holiday accommodation (e.g. holiday parks)
148| 4569| COMESTNI| Religious
148| 4570| COMESTNI| Staff/worker accommodation only
148| 4571| COMESTNI| Other
151| 4573| COBHRP| Europe
151| 4574| COBHRP| United Kingdom
151| 4575| COBHRP| Northern Ireland
151| 4576| COBHRP| England
151| 4577| COBHRP| Republic of Ireland
151| 4578| COBHRP| Scotland
151| 4579| COBHRP| Wales
151| 4580| COBHRP| Channel Islands and Isle of Man
151| 4581| COBHRP| Other Europe
151| 4582| COBHRP| EU countries
151| 4583| COBHRP| Member countries prior to 2004 expansion
151| 4584| COBHRP| Germany
151| 4585| COBHRP| Portugal
151| 4586| COBHRP| Other member countries prior to 2004 expansion
151| 4587| COBHRP| Accession countries 2004 onwards
151| 4588| COBHRP| Poland
151| 4589| COBHRP| Lithuania
151| 4590| COBHRP| Slovakia
151| 4591| COBHRP| Latvia
151| 4592| COBHRP| Romania
151| 4593| COBHRP| Other accession countries 2004 onwards
151| 4594| COBHRP| Europe (not otherwise specified)
151| 4595| COBHRP| Rest of Europe
151| 4596| COBHRP| Turkey
151| 4597| COBHRP| Russia
151| 4598| COBHRP| Other rest of Europe
151| 4599| COBHRP| Africa
151| 4600| COBHRP| North Africa
151| 4601| COBHRP| Central and Western Africa
151| 4602| COBHRP| Nigeria
151| 4603| COBHRP| Other Central and Western Africa
151| 4604| COBHRP| South and Eastern Africa
151| 4605| COBHRP| South Africa
151| 4606| COBHRP| Zimbabwe
151| 4607| COBHRP| Kenya
151| 4608| COBHRP| Other South and Eastern Africa
151| 4609| COBHRP| Africa (not otherwise specified)
151| 4610| COBHRP| Middle East and Asia
151| 4611| COBHRP| Middle East
151| 4612| COBHRP| Iran
151| 4613| COBHRP| Saudi Arabia
151| 4614| COBHRP| Other Middle East
151| 4615| COBHRP| Eastern Asia
151| 4616| COBHRP| China
151| 4617| COBHRP| Hong Kong
151| 4618| COBHRP| Other Eastern Asia
151| 4619| COBHRP| Southern Asia
151| 4620| COBHRP| India
151| 4621| COBHRP| Pakistan
151| 4622| COBHRP| Bangladesh
151| 4623| COBHRP| Other Southern Asia
151| 4624| COBHRP| South-East Asia
151| 4625| COBHRP| Philippines
151| 4626| COBHRP| East Timor
151| 4627| COBHRP| Malaysia
151| 4628| COBHRP| Thailand
151| 4629| COBHRP| Singapore
151| 4630| COBHRP| Other South-East Asia
151| 4631| COBHRP| Central Asia
151| 4632| COBHRP| North America and the Caribbean
151| 4633| COBHRP| USA
151| 4634| COBHRP| Canada
151| 4635| COBHRP| Caribbean
151| 4636| COBHRP| Other North America and the Caribbean
151| 4637| COBHRP| Central America
151| 4638| COBHRP| South America
151| 4639| COBHRP| Antarctica and Oceania
151| 4640| COBHRP| Australasia
151| 4641| COBHRP| Australia
151| 4642| COBHRP| New Zealand
151| 4643| COBHRP| Other Antarctica and Oceania
151| 4644| COBHRP| Other
151| 4646| COBHRP| Zambia
69| 4647| URESPOP| All usual residents in employment
69| 4648| URESPOP| All usual residents in communal establishments (excluding staff and their families)
69| 4649| URESPOP| All occupied household spaces
69| 4650| URESPOP| All usual residents not in employment
69| 4651| URESPOP| All households with students and schoolchildren aged 4 and over in full-time education who would reside in the area were they not living away from home during term time
7| 4652| AGESST| Age 16 and over
7| 4653| AGESST| Age 18 to 21
7| 4654| AGESST| Age 22 to 24
7| 4655| AGESST| Age 25 and over
148| 4656| COMESTNI| Defence (including ships)
148| 4657| COMESTNI| Other establishments
161| 4658| CARUNP| Working part-time outside the home
161| 4659| CARUNP| Working part-time at home
161| 4660| CARUNP| Working full-time outside the home
161| 4661| CARUNP| Working full-time at home
102| 4662| NUMLTHPD| This person is the only carer in the household
102| 4663| NUMLTHPD| Other
102| 4664| NUMLTHPD| Aged 0 to 15
102| 4665| NUMLTHPD| Aged 16 to 44
102| 4666| NUMLTHPD| Aged 45 to 59
102| 4667| NUMLTHPD| Aged 60 to 64
102| 4668| NUMLTHPD| Aged 65 to 74
102| 4669| NUMLTHPD| Aged 75 and over
154| 4670| COMTY| Adult care homes (including 'Local authority: Other homes' and 'Registered Social Landlord (Housing Association)')
56| 4672| PCOMST| Lived at same communal establishment one year ago
56| 4673| PCOMST| Lived elsewhere one year ago (including people aged under 1 [and so not born one year ago])
56| 4674| PCOMST| Staff or owner| or family member or partner of staff or owner (including people aged under 1 [and so not born one year ago])
91| 4675| AGEYDC| Age 12 to 18
144| 4676| DISTWRK| Other (including no fixed place of work| working on an offshore installation and working outside the UK)
164| 4677| DISTSTU| All categories: Distance travelled to place of study
164| 4678| DISTSTU| Study mainly at home
164| 4679| DISTSTU| Less than 2km
164| 4680| DISTSTU| 2km to less than 5km
164| 4681| DISTSTU| 5km to less than 10km
164| 4682| DISTSTU| 10km to less than 20km
164| 4683| DISTSTU| 20km to less than 30km
164| 4684| DISTSTU| 30km to less than 40km
164| 4685| DISTSTU| 40km to less than 60km
164| 4686| DISTSTU| 60km and over
164| 4687| DISTSTU| Other (including no fixed place of study and studying outside the UK)
165| 4688| NUMWRST| Total: Number of people working or studying in household
165| 4689| NUMWRST| One person working or studying in household
165| 4690| NUMWRST| Two people working or studying in household
165| 4691| NUMWRST| Three or more people working or studying in household
166| 4692| MTWSALT| Total: Method of travel to work or study (alternative classification)
166| 4693| MTWSALT| Driving a car or van
166| 4694| MTWSALT| 'Other' method of travel to work or study
166| 4695| MTWSALT| Works or studies at home
166| 4696| MTWSALT| Both driving cars or vans
166| 4697| MTWSALT| Both 'other' method of travel to work or study
166| 4698| MTWSALT| Both working or studying at home
166| 4699| MTWSALT| One driving a car or van| one 'other' method
166| 4700| MTWSALT| One driving a car or van| one working or studying at home
166| 4701| MTWSALT| One 'other' method| one working or studying at home
166| 4702| MTWSALT| All driving cars or vans
166| 4703| MTWSALT| All 'other' method of travel to work or study
166| 4704| MTWSALT| All working or studying at home
166| 4705| MTWSALT| Mixture of driving a car or van and 'other' method
166| 4706| MTWSALT| Mixture of driving a car or van and working or studying at home
166| 4707| MTWSALT| Mixture of 'other' method and working or studying at home
166| 4708| MTWSALT| Mixture of driving a car or van| 'other' and working or studying at home
167| 4709| DISTWS| All categories: Distance travelled to work or place of study
167| 4710| DISTWS| Work or study mainly at or from home
167| 4711| DISTWS| Less than 2km
167| 4712| DISTWS| 2km to less than 5km
167| 4713| DISTWS| 5km to less than 10km
167| 4714| DISTWS| 10km to less than 20km
167| 4715| DISTWS| 20km to less than 30km
167| 4716| DISTWS| 30km to less than 40km
167| 4717| DISTWS| 40km to less than 60km
167| 4718| DISTWS| 60km and over
167| 4719| DISTWS| Other (including no fixed place of work or study| working on an offshore installation and working or studying outside the UK)
159| 4720| MTTSTD| Train or underground| metro| light rail or tram
159| 4721| MTTSTD| All other methods of travel to study (including taxi or minicab| motorcycle| scooter or moped and other methods of travel not elsewhere specified)
102| 4722| NUMLTHPD| Aged 16 to 64
102| 4723| NUMLTHPD| Aged 65 and over
43| 4724| MTTWRK| Train| underground| metro| light rail| tram| bus| minibus or coach
144| 4725| DISTWRK| 30km and over
164| 4726| DISTSTU| Less than 5km
164| 4727| DISTSTU| 10km to less than 30km
164| 4728| DISTSTU| 30km and over
159| 4729| MTTSTD| Train| underground| metro| light rail| tram| bus| minibus or coach
166| 4730| MTWSALT| Mixture of driving a car or van| 'other' and working or studying at home (only applicable for households with three or more people working or studying)
165| 4731| NUMWRST| Two or more people working or studying in household
113| 4732| MTTWKS| Train| underground| metro| light rail| tram| bus| minibus or coach
113| 4733| MTTWKS| All other methods of travel to work or study
167| 4734| DISTWS| Less than 5km
167| 4735| DISTWS| 10km to less than 30km
167| 4736| DISTWS| 30km and over
159| 4737| MTTSTD| All other methods of travel to study
69| 4738| URESPOP| All people aged 4 and over studying the week before the census (including full-time students whether or not working| and other students who are not working but excluding some 4 and 5-year-olds)
69| 4739| URESPOP| All households with at least one person working or studying (persons in employment the week before the census and full-time students)
69| 4740| URESPOP| All people aged 4 and over studying or aged 16 to 74 in employment the week before the census (excluding some 4 and 5-year-olds)
69| 4742| URESPOP| All people aged 16 to 74 in employment the week before the census (excluding full-time students)
126| 4743| ETHGRSC| Other Asian (including Bangladeshi| Bangladeshi Scottish or Bangladeshi British; Chinese| Chinese Scottish or Chinese British; and Other Asian)
158| 4744| EGHRPSC| Other Asian (including Bangladeshi| Bangladeshi Scottish or Bangladeshi British; Chinese| Chinese Scottish or Chinese British; and Other Asian)
92| 4745| CONFAM| No children
92| 4746| CONFAM| With dependent children
92| 4747| CONFAM| All children non-dependent
149| 4748| DEPCHILDHH| Youngest aged 5 to 7
149| 4749| DEPCHILDHH| Youngest aged 8 to 9
149| 4750| DEPCHILDHH| Youngest aged 10 to 11
149| 4751| DEPCHILDHH| Youngest aged 12 to 15
121| 4752| GLANGS| Can understand| speak| read or write Gaelic
30| 4753| HHSIZE| 2 or more people in household
103| 4754| BORNIN| Born in the UK
103| 4755| BORNIN| Born outside the UK
69| 4756| URESPOP| All parents aged 16 and over with dependent children
62| 4757| RESTYP| Lives in a communal establishment (including people enumerated as sleeping rough)
35| 4758| INDUST| E Water supply; sewerage| waste management and remediation activities
98| 4759| PARWRK| Couple family
98| 4760| PARWRK| Lone parent family
66| 4761| TENURE| Other than private landlord or letting agency
19| 4763| ECPHRP| Full-time (including full-time students)
19| 4764| ECPHRP| Part-time (including full-time students)
19| 4765| ECPHRP| Self-employed (including full-time students)
19| 4766| ECPHRP| Economically active: Unemployed (including full-time students)
6| 4767| AGEHRP| Age 16 and over
52| 4768| NUMRMS| 2 to 3 rooms
52| 4769| NUMRMS| 4 to 5 rooms
52| 4770| NUMRMS| 6 or more rooms
172| 4771| STUACCALT| Total: Student accommodation
172| 4772| STUACCALT| Student living alone
172| 4773| STUACCALT| Living with parents in one family unit household
172| 4774| STUACCALT| Living with parents - other
172| 4775| STUACCALT| In one family unit household with spouse| partner or offspring
172| 4776| STUACCALT| Living in all-student household
172| 4777| STUACCALT| Other household type
172| 4778| STUACCALT| Living in a communal establishment
66| 4779| TENURE| Social rented
66| 4780| TENURE| Private rented or living rent-free
69| 4781| URESPOP| Full-time students (including full-time students living in a communal establishment)
19| 4782| ECPHRP| Self-employed
19| 4783| ECPHRP| Part-time (including full-time students)
19| 4784| ECPHRP| Full-time (including full-time students)
6| 4785| AGEHRP| Age 16 to 34
69| 4786| URESPOP| All people in households working or studying in the week before the census
173| 4787| EGRSCALT| Total: Ethnic group (alternative classification Scotland)
173| 4788| EGRSCALT| White
173| 4789| EGRSCALT| Other ethnic groups (all ethnic groups other than White)
174| 4790| DAYPOP| Daytime population
174| 4791| DAYPOP| Daytime population in households
175| 4792| CDPOPLGD| A. Usual residents in this Local Government District
175| 4793| CDPOPLGD| B. People who work or study and live in this Local Government District
175| 4794| CDPOPLGD| C. People who live in this Local Government District but neither work nor study
175| 4795| CDPOPLGD| D. People who work or study in this Local Government District and live elsewhere in Northern Ireland
175| 4796| CDPOPLGD| E. Daytime population (B+C+D)
176| 4797| RURDPLGD| A. Usual residents in this Local Government District
176| 4798| RURDPLGD| B. People who live in this Local Government District and work or study anywhere
176| 4799| RURDPLGD| C. People who live in this Local Government District and work or study outside Northern Ireland (B-F-G)
176| 4800| RURDPLGD| D. People who live in this Local Government District and work or study in Northern Ireland (B-C)
176| 4801| RURDPLGD| E. People who work or study in this Local Government District and live in Northern Ireland
176| 4802| RURDPLGD| F. People who work or study and live in this Local Government District
176| 4803| RURDPLGD| G. People who live in this Local Government District but work or study elsewhere in Northern Ireland
176| 4804| RURDPLGD| H. People who works or study in this Local Government District and live elsewhere in Northern Ireland
176| 4805| RURDPLGD| I. People who live in this Local Government District but neither work nor study
176| 4806| RURDPLGD| K. Excluded (those who gave inconsistent information between their employment status and their address of work or study)
176| 4807| RURDPLGD| L. Daytime population (F+H+I) (A-C-G+H-K)
132| 4808| PASSC1| Europe
132| 4809| PASSC1| Europe: United Kingdom (including British Overseas Territories)
132| 4810| PASSC1| Europe: Ireland
132| 4811| PASSC1| Other Europe
132| 4812| PASSC1| Other Europe: EU Countries
132| 4813| PASSC1| Other Europe: Non-EU countries
132| 4814| PASSC1| Africa
132| 4815| PASSC1| Middle East and Asia
132| 4816| PASSC1| The Americas and the Caribbean
132| 4817| PASSC1| The Americas and the Caribbean: North America and the Caribbean
132| 4818| PASSC1| The Americas and the Caribbean: Central America
132| 4819| PASSC1| The Americas and the Caribbean: South America
132| 4820| PASSC1| Antarctica and Oceania
133| 4821| PASSC2| Other (including British Overseas Territories)
18| 4822| ECOACT| In employment and currently working
113| 4823| MTTWKS| Other method (including no fixed place of work or study)
113| 4824| MTTWKS| Not in employment or a full-time student
167| 4825| DISTWS| No fixed place
167| 4826| DISTWS| Not currently in employment or a full-time student
167| 4827| DISTWS| Total distance (km)
167| 4828| DISTWS| Average distance (km)
177| 4829| CWPOPLGD| People who live in this Local Government District
177| 4830| CWPOPLGD| People who live in this Local Government District who are in employment
177| 4831| CWPOPLGD| A. People who live in this Local Government District and are in employment in Northern Ireland (B+C)
177| 4832| CWPOPLGD| B. People who live in and are in employment in this Local Government District
177| 4833| CWPOPLGD| C. People who are in employment outside the Local Government District they live in but still within Northern Ireland
177| 4834| CWPOPLGD| D. People who live outside but are in employment in this Local Government District
177| 4835| CWPOPLGD| E. Total workplace population (B+D)
37| 4836| LLHPDI| Day-to-day activities limited
92| 4837| CONFAM| All children non-dependent
92| 4838| CONFAM| Dependent children
92| 4839| CONFAM| No children
174| 4840| DAYPOP| Density of Daytime Population (number of persons per Hectare)
174| 4841| DAYPOP| Density of Workplace Population (number of persons per Hectare)
174| 4843| DAYPOP| Workplace population (Age 16 to 74 excluding students)
179| 4844| CWPOPNI| People who live in Northern Ireland
179| 4845| CWPOPNI| People who live in Northern Ireland who are in employment
179| 4846| CWPOPNI| Total Workplace population
180| 4847| CDPOPNI| A. Usual residents in Northern Ireland
180| 4848| CDPOPNI| B. People who work or study and live in the same Local Government District
180| 4849| CDPOPNI| C. People who live in Northern Ireland but neither work nor study
180| 4850| CDPOPNI| D. People who work or study in a Local Government District and live elsewhere in Northern Ireland
180| 4851| CDPOPNI| E. Daytime population (B+C+D)
181| 4852| RURDPNI| A. Usual Residents in Northern Ireland
181| 4853| RURDPNI| B. People who live in Northern Ireland and work or study anywhere
181| 4854| RURDPNI| C. People who live in Northern Ireland and work or study outside Northern Ireland (B-F-G)
181| 4855| RURDPNI| D. People who live in Northern Ireland and work or study in Northern Ireland
181| 4856| RURDPNI| E. People who work or study and live in Northern Ireland
181| 4857| RURDPNI| F. People who work or study and live in the same Local Government District
181| 4858| RURDPNI| G. People who live in a Local Government District but work or study elsewhere in Northern Ireland
181| 4859| RURDPNI| H. People who work or study in a Local Government District and live elsewhere in Northern Ireland
181| 4860| RURDPNI| I. People who live in Northern Ireland but neither work nor study
181| 4861| RURDPNI| K. Excluded (those who gave inconsistent information between their employment status and their address of work or study)
181| 4862| RURDPNI| L. Daytime population (F+H+I) (A-C-G+H-K)
182| 4863| MNLANNI| Total: Main language (Northern Ireland)
182| 4864| MNLANNI| English
182| 4865| MNLANNI| Portuguese
174| 4866| DAYPOP| Workday population
18| 4867| ECOACT| Full-time student
75| 4868| PPHALL| Ghana
75| 4869| PPHALL| Nigeria
75| 4870| PPHALL| Other Central and Western Africa
75| 4871| PPHALL| Kenya
75| 4872| PPHALL| Somalia
75| 4873| PPHALL| South Africa
75| 4874| PPHALL| Zimbabwe
75| 4875| PPHALL| Other South and Eastern Africa
75| 4876| PPHALL| Iran
75| 4877| PPHALL| Iraq
75| 4878| PPHALL| Other Middle East
75| 4879| PPHALL| China
75| 4880| PPHALL| Hong Kong (Special Administrative Region of China)
75| 4881| PPHALL| Japan
75| 4882| PPHALL| Other Eastern Asia
75| 4883| PPHALL| Afghanistan
75| 4884| PPHALL| Bangladesh
75| 4885| PPHALL| India
75| 4886| PPHALL| Pakistan
75| 4887| PPHALL|  Sri Lanka
75| 4888| PPHALL| Other Southern Asia
75| 4889| PPHALL| Malaysia
75| 4890| PPHALL| Philippines
75| 4891| PPHALL| Singapore
75| 4892| PPHALL| Other South-East Asia
75| 4893| PPHALL| North America
75| 4894| PPHALL| Canada
75| 4895| PPHALL| United States
75| 4896| PPHALL| The Caribbean
75| 4897| PPHALL| Jamaica
75| 4898| PPHALL| Other Caribbean
75| 4899| PPHALL| Australasia
75| 4900| PPHALL| Australia
75| 4901| PPHALL| New Zealand
75| 4902| PPHALL| Other Oceania
183| 4903| OOTT| All usual residents living in the area out of term-time
183| 4904| OOTT| Density (number of persons per Hectare)
72| 4905| WELLANGS| Studies in England
69| 4906| URESPOP| All usual residents in families
174| 4907| DAYPOP| Workplace population (Age 16 and over)
112| 4917| COMESTR| Local Authority
112| 4918| COMESTR| Children's home (including secure units)
112| 4919| COMESTR| Care home or other home
69| 4920| URESPOP| Full-time students and schoolchildren aged 4 and over living away from home during term time
50| 4921| NUMAHH| Other households (not 1 adult in household)
174| 4922| DAYPOP| Workplace population (excluding students [Northern Ireland only])
174| 4923| DAYPOP| Density of Workplace Population (number of persons per Hectare excluding students [Northern Ireland only])
18| 4924| ECOACT| Economically active (including full-time students)
18| 4925| ECOACT| In employment
18| 4926| ECOACT| Long-term unemployed
18| 4927| ECOACT| Employee
18| 4928| ECOACT| Self-employed without employees
18| 4929| ECOACT| Part-time
18| 4930| ECOACT| Full-time
18| 4931| ECOACT| Self-employed with employees
18| 4932| ECOACT| Part-time
18| 4933| ECOACT| In employment the week before the census (including full-time students)
18| 4935| ECOACT| Full-time
18| 4936| ECOACT| Self-employed
18| 4937| ECOACT| Unemployed (including full time students)
18| 4938| ECOACT| Unemployed (excluding full-time students)
18| 4939| ECOACT| Unemployed (full-time students only)
6| 4940| AGEHRP| Age 16 to 44
6| 4941| AGEHRP| Age 45 to 74
184| 4942| ECOSTAT| Total: Economic status
184| 4943| ECOSTAT| In employment
184| 4944| ECOSTAT| Part-time
184| 4945| ECOSTAT| Full-time
184| 4946| ECOSTAT| Not in employment
184| 4947| ECOSTAT| Retired
184| 4948| ECOSTAT| Long-term sick or disabled
184| 4949| ECOSTAT| Other (including students| those looking after home/family| unemployed and others)
184| 4950| ECOSTAT| Student (including full-time students)
184| 4951| ECOSTAT| Other
162| 4952| STUACC| University (for example| halls of residence)
162| 4953| STUACC| Living in a one-family household with spouse| partner or children
69| 4955| URESPOP| All usual residents who work mainly at or from home
185| 4956| ARMFOR| Member of the Armed Forces
185| 4957| ARMFOR| All HRPs who are members of the Armed Forces and are usual residents and all associated persons in households with members of the Armed Forces who are also usual residents
185| 4958| ARMFOR| All associated people aged 16 and over who are usual residents in households with members of the Armed Forces who are also usual residents
185| 4959| ARMFOR| Member of the Foreign Armed Forces
24| 4960| FAMSTA| No children
24| 4961| FAMSTA| No children
3| 4962| AGE| Age 16 to 18
3| 4963| AGE| Age 19 to 24
97| 4964| MAINLAN| Sign language
145| 4965| MTW2001| Train| underground| metro| light rail or tram
16| 4966| DPCHDF| Aged 10 to 15
16| 4967| DPCHDF| Youngest aged 10 to 15
16| 4968| DPCHDF| Youngest aged 10 to 15
16| 4969| DPCHDF| Youngest aged 0 to 9
16| 4970| DPCHDF| Youngest aged 10 to 18
90| 4971| AGEFRP| Age 25 to 49
28| 4972| HHDCOM| Married| same-sex civil partnership or cohabiting couple
51| 4973| NUMBED| 4 or more bedrooms
86| 4974| AGEDEP| Age 15 to 16
86| 4975| AGEDEP| Age 17 to 18
86| 4976| AGEDEP| Age 3 to 11
86| 4977| AGEDEP| Age 12 to 18
7| 4978| AGESST| Schoolchildren and full-time students at their non-term-time address
7| 4979| AGESST| Age 4 and over
7| 4980| AGESST| Age 4 to 15
7| 4981| AGESST| Age 16
7| 4982| AGESST| Age 17
7| 4983| AGESST| Age 18
7| 4984| AGESST| Age 19
7| 4985| AGESST| Age 20 to 21
7| 4986| AGESST| Age 22 to 24
7| 4987| AGESST| Age 25 and over
69| 4988| URESPOP| All parents aged 16 and over with dependent children in family
86| 4989| AGEDEP| Age 0 to 9
86| 4990| AGEDEP| Age 10 to 18
93| 4991| EXWHHCO| One adult can speak Welsh
93| 4992| EXWHHCO| Two or more adults can speak Welsh
93| 4993| EXWHHCO| One adult can speak Welsh
144| 4994| DISTWRK| Less than 10km
144| 4995| DISTWRK| 10km and over
144| 4996| DISTWRK| Other
184| 4997| ECOSTAT| Employee
184| 4998| ECOSTAT| Self-employed
184| 4999| ECOSTAT| With employees
184| 5000| ECOSTAT| Without employees
186| 5001| CHILFAM| Total: Children in family
186| 5002| CHILFAM| One dependent child in family
186| 5003| CHILFAM| Two or more dependent children in family
186| 5004| CHILFAM| All children in family non-dependent
187| 5005| FAMCOMP| Total: Dependent children in family (condensed for England and Wales)
187| 5006| FAMCOMP| Families without children
187| 5007| FAMCOMP| Families with children
187| 5008| FAMCOMP| Dependent children
187| 5009| FAMCOMP| Youngest aged under 10
187| 5010| FAMCOMP| Youngest aged 10 to 18
187| 5011| FAMCOMP| Non-dependent children
187| 5012| FAMCOMP| Youngest aged under 5
187| 5013| FAMCOMP| Youngest aged 5 to 7
187| 5014| FAMCOMP| Youngest aged 8 to 9
187| 5015| FAMCOMP| Youngest aged 10 to 11
187| 5016| FAMCOMP| Youngest aged 12 to 15
187| 5017| FAMCOMP| Youngest aged 16 to 18
55| 5018| PASHLD| UK passport
55| 5019| PASHLD| Non-UK passport
188| 5020| PLRES1YA| Total: Place of residence one year before the census
188| 5021| PLRES1YA| Lived at same communal establishment one year before the census
188| 5022| PLRES1YA| Didn't live at same communal establishment one year before the census
166| 5023| MTWSALT| One person working or studying
166| 5024| MTWSALT| Two people working or studying
166| 5025| MTWSALT| Three or more people working or studying