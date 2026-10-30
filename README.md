# Awesome Dubai Real Estate [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of data sources, tools, regulators, portals, and proptech for Dubai real estate.

Dubai's property market is unusually transparent: every sale, rent, and off-plan registration flows through the Dubai Land Department and much of it is published as open data. This list gathers the official sources, the tools built on top of them, and the services you actually need to buy, rent, invest, analyse, or build products in this market.

## Contents

- [Market at a Glance](#market-at-a-glance)
- [Regulators & Official Services](#regulators--official-services)
- [Open Data & Market Analytics](#open-data--market-analytics)
- [Listing Portals](#listing-portals)
- [Off-Plan & Developers](#off-plan--developers)
- [Brokerages](#brokerages)
- [Agents & Public Faces](#agents--public-faces)
- [Funds, REITs & Institutional Investors](#funds-reits--institutional-investors)
- [Mortgages & Financing](#mortgages--financing)
- [Fractional Investing & Tokenization](#fractional-investing--tokenization)
- [Renting & Tenancy](#renting--tenancy)
- [Short-Term Rentals](#short-term-rentals)
- [Property Management & Services](#property-management--services)
- [Visas for Property Investors](#visas-for-property-investors)
- [Laws & Regulations](#laws--regulations)
- [Market Reports & Research](#market-reports--research)
- [News & Media](#news--media)
- [Media, Podcasts & Newsletters](#media-podcasts--newsletters)
- [Developer Resources](#developer-resources)
- [Key Numbers](#key-numbers)

## Market at a Glance

Headline figures from the Dubai Land Department (DLD) and Dubai Media Office. Dubai does not have a single "official" developer or brokerage league table, so rankings below come from DLD transaction data as compiled by DXB Interact.

| Period          | Figure                                                                                                                                   | Source                                                                                                                                                                 |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2025 full year  | AED 917 billion across 270,000+ transactions (+20% in value), 193,100 investors of which 129,600 were new                                | [Dubai Media Office](https://www.mediaoffice.ae/en/news/2026/january/12-01/dubais-real-estate-market-records-new-historic-milestone)                                   |
| 2025 sales only | AED 682.5 billion in sales (+30.6%); off-plan was 72.9% of sales transactions                                                            | [Cavendish Maxwell FY2025](https://cavendishmaxwell.com/resources/uploads/2026/02/Dubai-Residential-Market-Performance_FY2025.pdf)                                     |
| 2025 brokers    | AED 13.59 billion in commissions (+31%) on 96,440 broker-executed deals; 29,577 registered brokers and 1,223 offices by mid-2025         | [Dubai Media Office](https://www.mediaoffice.ae/en/news/2025/july/26-07/brokers-cement-their-role-in-dubai-real-estate-market-contributing-to-over-42000-transactions) |
| Q1 2026         | AED 252 billion (+31% in value, +6% in volume)                                                                                           | [Dubai Media Office](https://mediaoffice.ae/en/news/2026/april/09-04/dubai-real-estate-transactions-surge-31-to-reach-aed252-billion-in-q1-2026)                       |
| H1 2026         | AED 419.9 billion across 112,850 transactions; sales AED 286.4 billion, of which off-plan AED 139.8 billion                              | [Emirates 24/7](https://www.emirates247.com/business/dubai-property-transactions-reach-aed4199-billion-in-first-half-of-2026/3800)                                     |
| 9M 2026         | Sales above AED 380 billion on 123,000+ deals, the second-highest nine-month total ever but about 23% below 9M 2025 as the market cooled | [W Capital via Zawya](https://www.zawya.com/en/press-release/research-studies/dubai-real-estate-sales-record-second-highest-nine-month-level-on-record-1459108)        |
| Strategy 2033   | DLD targets: transactions +70%, market value AED 1 trillion, home ownership 33%, sector GDP contribution to AED 73 billion               | [Dubai Media Office](https://www.mediaoffice.ae/en/news/2024/october/29-10/dubai-real-estate-sector-strategy-2033)                                                     |

**2025 developer league table** (DLD-registered sales compiled by DXB Interact, reported by [ME Construction News](https://meconstructionnews.com/65908/dubai-real-estate-shows-robust-demand-for-luxury-and-affordable-offerings/amp)):

| Rank | By value (USD)   | By number of deals |
| ---- | ---------------- | ------------------ |
| 1    | Emaar 17.9 bn    | Binghatti 17,061   |
| 2    | Damac 9.8 bn     | Damac 15,393       |
| 3    | Binghatti 7.1 bn | Emaar 13,149       |
| 4    | Nakheel 6.7 bn   | Sobha 9,698        |
| 5    | Sobha 6.1 bn     | Samana 4,754       |
| 6    | Meraas 5.7 bn    | Nakheel 4,160      |
| 7    | Omniyat 3.0 bn   | Danube 4,089       |
| 8    | Aldar 2.7 bn     | Azizi 3,479        |
| 9    | H&H 2.2 bn       | Imtiaz 2,679       |
| 10   | Danube 1.9 bn    | Meraas 2,385       |

## Regulators & Official Services

- [Dubai Land Department (DLD)](https://dubailand.gov.ae) - The authority that registers every property transaction, licenses brokers, and publishes market data.
- [Dubai REST](https://dubailand.gov.ae/en/eservices/dubai-rest/) - Official DLD app to verify ownership, check service charges, view project status, and pay fees.
- [Ejari](https://dubailand.gov.ae/en/eservices/request-to-register-and-renew-ejari-contract/) - Mandatory tenancy contract registration that is required for visas, DEWA, and disputes.
- [Mollak](https://mollak.gov.ae) - Service charge accounting system for jointly owned properties.
- [Trakheesi](https://trakheesi.gov.ae) - Permit system every property advertisement must carry a number from.
- [Rental Dispute Centre](https://rdc.gov.ae) - The judicial arm of DLD where landlord and tenant disputes are filed.
- [Dubai Brokers](https://dubailand.gov.ae/en/eservices/licensed-real-estate-brokers/licensed-real-estate-brokers-list) - Official register to verify whether a broker is RERA-licensed.
- [Dubai Municipality](https://www.dm.gov.ae) - Building permits, completion certificates, and the Makani geo-address system.
- [DEWA](https://www.dewa.gov.ae) - Electricity and water connection, which requires Ejari and a security deposit.
- [Dubai Courts](https://www.dc.gov.ae) - Notary services for powers of attorney and eviction notices.
- [UAE Central Bank](https://www.centralbank.ae/en) - Sets mortgage loan-to-value caps and lending rules.
- [Dubai 2040 Urban Master Plan](https://u.ae/en/about-the-uae/strategies-initiatives-and-awards/strategies-plans-and-visions/transport-and-infrastructure/dubai-2040-urban-master-plan) - The planning framework shaping where the city grows next.

## Open Data & Market Analytics

- [DLD Open Data](https://dubailand.gov.ae/en/open-data/) - Downloadable datasets of sales transactions, rents, valuations, projects, brokers, and more.
- [Dubai Pulse](https://www.dubaipulse.gov.ae) - City open data platform that hosts the DLD datasets with APIs.
- [DXB Interact](https://dxbinteract.com) - Free interactive dashboards of every DLD transaction, filterable by area, building, and date.
- [Data Habibi](https://datahabibi.com) - Browse sales and rental transactions building by building with price history.
- [Property Monitor](https://propertymonitor.com) - Market intelligence, price index, and valuations used by banks and agents.
- [REIDIN](https://reidin.com) - Subscription data provider with indices and transaction feeds for the UAE.
- [RERA Rental Index](https://dubailand.gov.ae/en/eservices/rental-index/) - Official calculator for how much rent can legally increase on renewal.
- [Bayut Market Reports](https://www.bayut.com/mybayut/category/real-estate/market-report/) - Quarterly and annual trend reports built from portal search and transaction data.
- [Property Finder Insights](https://www.propertyfinder.ae/en/insights) - Market trends, price indices, and area performance.
- [Dubai Statistics Center](https://www.dsc.gov.ae) - Official population and economic statistics that drive housing demand.
- [ValuStrat](https://valustrat.com) - Monthly price index and valuation reports for Dubai residential.
- [Cavendish Maxwell](https://www.cavendishmaxwell.com) - Valuation firm publishing detailed quarterly market reports.
- [Asteco](https://www.asteco.com) - Long-running quarterly reports on rents and sales across the UAE.

## Listing Portals

- [Property Finder](https://www.propertyfinder.ae) - Largest portal in the UAE for sale and rental listings with verified agents.
- [Bayut](https://www.bayut.com) - Major portal with area guides, floor plans, price trends, and transaction history.
- [Dubizzle Property](https://dubai.dubizzle.com/property-for-rent/) - Classifieds-style listings, strong for rentals and direct-from-owner deals.
- [JamesEdition](https://www.jamesedition.com/real_estate/dubai-united-arab-emirates) - International luxury listings including Dubai.

## Off-Plan & Developers

Each entry gives founding year, ownership, flagship communities, and the latest reported numbers so you can judge scale and track record rather than marketing.

- [Oqood](https://oqood.ae) - DLD system that registers off-plan sales so buyers can verify their contract.
- [Project Status Tracker](https://dubailand.gov.ae/en/eservices/real-estate-project-status-landing/real-estate-project-status) - Official completion percentage and escrow status of every registered project.
- [Emaar](https://www.emaar.com) - Founded 1997 by Mohamed Alabbar, listed on DFM with the Dubai government as anchor shareholder. Downtown Dubai, Dubai Creek Harbour, Dubai Hills Estate, Emaar Beachfront. 2025: property sales AED 80.4 billion (+16%), revenue AED 49.6 billion, backlog AED 155 billion, and number one by value in DLD data ([results](https://www.wam.ae/en/article/bypcc9s-emaar-achieves-another-record-year-with-highest), [Instagram](https://www.instagram.com/emaardubai/)).
- [Nakheel](https://www.nakheel.com) - Founded 2003, government-owned and folded into Dubai Holding together with Meydan in March 2024. Palm Jumeirah, Palm Jebel Ali, Dubai Islands, The World. 2025: USD 6.7 billion across 4,160 deals, fourth by value; Palm Jebel Ali logged 605 villa deals against 136 on Palm Jumeirah ([Instagram](https://www.instagram.com/nakheelofficial/)).
- [Meraas](https://www.meraas.com) - Founded 2007, part of Dubai Holding since 2020. Bluewaters, City Walk, La Mer, Jumeira Bay, Port de La Mer. 2025: USD 5.7 billion across 2,385 deals; a Bulgari Lighthouse penthouse sold for AED 282 million ([Instagram](https://www.instagram.com/meraasdubai/)).
- [Dubai Properties](https://www.dp.ae) - Founded 2002, the Dubai Holding arm behind JBR, Business Bay, Mudon, and Villanova. Dubai Holding Real Estate now groups Meraas, Nakheel, Meydan, and Dubai Properties under CEO Khalid Al Malik.
- [Damac](https://www.damacproperties.com) - Founded 2002 by Hussain Sajwani, listed in 2015 and taken private again in 2022. DAMAC Hills, Lagoons, Islands, Riverside. 2025: AED 36 billion in sales, the largest private developer; DAMAC Islands 2 took AED 11 billion in about five hours. H1 2026: number one off-plan seller by volume with 5,706 units and AED 15.6 billion ([results](https://gulfnews.com/business/property/damac-posts-dh36-billion-in-2025-sales-tops-dubais-private-developers-1.500414593)).
- [Sobha Realty](https://www.sobharealty.com) - Founded by P.N.C. Menon, whose Sobha group dates to 1976; privately held under PNC Investments, chaired by Ravi Menon. Sobha Hartland, Hartland II, Sobha One, Siniya Island. 2025: sales AED 30 billion (+30%), revenue AED 14.1 billion, net profit AED 4.0 billion; 6,819 units scheduled for handover in 2026 ([results](https://sobharealty.com/media-center/press-releases/sobha-realty-30-percent-growth-2025), [Instagram](https://www.instagram.com/sobharealty/)).
- [Binghatti](https://www.binghatti.com) - Founded 2008 by Dr. Hussain BinGhatti, private with listed sukuk. Bugatti Residences, Burj Binghatti Jacob & Co, Mercedes-Benz Places. 2025: number one by deal count with 17,061 deals; revenue AED 12.43 billion (+96%), net profit AED 3.58 billion, sales AED 17.68 billion, seven project completions ([results](https://www.binghatti.com/en/pr/binghatti-holding-fy-2025-financial-results), [Instagram](https://www.instagram.com/binghatti/)).
- [Omniyat](https://www.omniyat.com) - Founded 2005 by Mahdi Amjad, private. One at Palm Jumeirah, The Opus, Orla, AVA, Vela, Alba with Dorchester Collection. 2025: group sales AED 20 billion, revenue AED 4.1 billion (+150%), net profit AED 1.2 billion, USD 900 million raised in sukuk ([results](https://www.omniyat.com/news/omniyat-group-delivers-exceptional-financial-performance-in-2025), [Instagram](https://www.instagram.com/omniyatofficial/)).
- [Azizi Developments](https://www.azizidevelopments.com) - Founded 2007 by Mirwais Azizi, private. Riviera, Venice, the 725-metre Burj Azizi, and the AED 75 billion Azizi Milan. 2025: AED 16 billion in unit sales with a 2026 target of AED 30 billion and 22 deliveries.
- [Danube Properties](https://danubeproperties.com) - Property arm launched 2014 by Rizwan Sajan, whose Danube group dates to 1993; private. Known for the 1% monthly payment plan. Bayz, Oceanz, and Shahrukhz, which sold out on launch day in December 2025. 2025: USD 1.9 billion across 4,089 deals ([Instagram](https://www.instagram.com/danubeproperties/)).
- [Samana Developers](https://www.samanadevelopers.com) - Founded by Imran Farooq, private. 2025: gross sales AED 7.1 billion, fifth-largest off-plan seller, 16 launches, 12,000 units under construction; planning a sukuk and a possible 2026 IPO ([Instagram](https://www.instagram.com/samana.developers/)).
- [Ellington Properties](https://ellingtonproperties.ae) - Founded 2014 by Robert Booth, Joseph Thomas, and Elie Naaman; private, design-led. Belgravia, One River Point, Mercer House, Ellington Cove on Dubai Islands ([Instagram](https://www.instagram.com/ellingtondubai/)).
- [Select Group](https://www.select-group.ae) - Founded 2002 by Rahail Aslam, private. Peninsula in Business Bay (3,334 units, sold out 2024) and the 122-floor Six Senses Residences Dubai Marina; more than 10,000 homes delivered ([Instagram](https://www.instagram.com/selectgroupuae/)).
- [Deyaar](https://www.deyaar.ae) - Founded 2002, listed on DFM with Dubai Islamic Bank holding about 45%. 2025: revenue AED 1.97 billion (+30%), pre-tax profit AED 638 million, pipeline about AED 7 billion ([Instagram](https://www.instagram.com/deyaarofficial/)).
- [MAG](https://www.mag.ae) - Group founded 1978 by Moafaq Al Gaddah, private. Keturah Reserve in Meydan and the USD 6 billion Keturah Ardh with CITIC ([Instagram](https://www.instagram.com/maggroupholding/)).
- [Imtiaz Developments](https://www.imtiaz.ae) - Construction roots from 1993, now the largest private developer on Dubai Islands with 15 projects there. 2025: 2,679 deals, ninth by volume.
- [Object 1](https://object-1.com) - Part of TSZ Group, led by CEO Tatiana Tonu. H1 2025 sales value up 188% year on year on DLD data ([Instagram](https://www.instagram.com/object1.uae/)).
- [H&H Development](https://h-h.ae) - Founded 2007 by Shahab Lutfi and Mohamed Al Hussaini. Aman Dubai, Eden House Za'abeel, Dubai Peninsula. 2025: USD 2.2 billion, ninth by value ([Instagram](https://www.instagram.com/h.h_development/)).
- [Aldar](https://www.aldar.com) - Abu Dhabi's listed master developer, founded 2004, entering Dubai through a joint venture with Dubai Holding (Haven, Athlon, The Wilds) that was expanded in February 2026 to about 14,000 homes with a gross development value above AED 38 billion. 2025 group sales AED 40.6 billion, Dubai USD 2.7 billion.
- [Arada](https://www.arada.com) - Founded 2017, headquartered in Dubai, private. Armani Beach Residences on Palm Jumeirah and W Residences Dubai Harbour. 2025: sales AED 17.3 billion (+199%) on 5,140 units ([Instagram](https://www.instagram.com/aradaliving/)).
- [wasl](https://www.wasl.ae) - Established 2008 by the government's Dubai Real Estate Corporation. wasl1, wasl gate, wasl village; 45,000 affordable rental units make up 85% of its portfolio.
- [Expo City Dubai](https://expocitydubai.com) - Government-owned district opened in October 2022 on the Expo 2020 site. Mangrove, Sky, Sidr Residences, Expo Valley ([Instagram](https://www.instagram.com/expocitydubai/)).
- [Tilal Al Ghaf](https://www.tilalalghaf.com) - Majid Al Futtaim's master community launched 2018 with completion due 2027; Lanai Islands set a AED 200 million mansion record, followed by Ghaf Woods in 2024.
- [Reelly](https://reelly.io) - Off-plan database and sales platform for brokers with unit-level availability.
- [Alnair](https://alnair.ae) - Off-plan project catalogue with payment plans and launch calendars.

## Brokerages

Dubai had 29,577 registered brokers in 1,223 offices by mid-2025. The firms below are the ones that consistently top portal awards, developer broker awards, and DLD volume, with founding year, size, and 2025 results where published.

- [Betterhomes](https://www.bhomes.com) - Founded 1986 by Linda Mahoney, the oldest major brokerage; 400+ consultants, full-service including leasing and property management. 2025: own transactions up 24% in Q3 and leasing deals up 60%; publishes widely cited quarterly reports ([Instagram](https://www.instagram.com/betterhomesuae)).
- [Allsopp & Allsopp](https://www.allsoppandallsopp.com) - Founded 2008 by brothers Lewis (chairman) and Carl Allsopp (CEO); 650+ staff across Business Bay and Motor City. 2025: company sales record broken twice, Darren Murphy passed AED 1 billion in personal sales and won Property Finder's Top Closer award; record AED 107 million Al Barari villa ([Instagram](https://www.instagram.com/allsoppandallsopp)).
- [fäm Properties](https://famproperties.com) - Founded 2009 by Firas Al Msaddi; 650 to 750 agents in 22+ community branches, the largest brokerage by headcount. Bayut Agency of the Year 2025; owns the DXB Interact data platform ([Instagram](https://www.instagram.com/famproperties)).
- [haus & haus](https://www.hausandhaus.com) - Founded 2013 by James Perry, Luke Remington, and Simon Baker. Subject of the BBC Three series Dubai Hustle; its Cathal O'Neill was Bayut Agent of the Year 2025; runs the Dubai Real Estate Unplugged podcast ([Instagram](https://www.instagram.com/hausandhaus)).
- [White & Co](https://whiteandcorealestate.com) - Founded January 2021 by Calum White; about 400 brokers and 200 salaried staff in a four-floor Motor City headquarters. 2025: turnover GBP 63 million (+75%), profit GBP 8.6 million, targeting GBP 83 million in 2026; Property Finder Rent Champion for Palm Jumeirah ([founder interview](https://gulfnews.com/podcasts/gn-talks/from-8-to-400-brokers-in-3-years-calum-white-on-building-dubais-fastest-growing-real-estate-firm-1.500176105)).
- [Strada](https://www.stradauae.com) - Founded 2022 by Chae Simons, Gary Allen, and Gino Cross; video-led marketing brokerage focused on the secondary market. 130 staff by September 2024 with revenue up 309% year on year; dubizzle Agency of the Month August 2024 ([Instagram](https://www.instagram.com/stradauae)).
- [Dacha Real Estate](https://www.dacha.ae) - Founded 2004, boutique luxury agency on Palm Jumeirah and Dubai Marina with a strong Russian-speaking client base, led by CEO Alessia Sheglova. Bayut People's Choice Premium Agency of the Year 2024 ([Instagram](https://www.instagram.com/dacharealestate)).
- [Driven Properties](https://www.drivenproperties.com) - Founded 2012 by Abdullah Alajaji; 650+ staff with offices in Saudi Arabia, China, Egypt, Spain, India, and Japan. Property Finder Quality Brokerage of the Year 2025; bought its Emaar Square headquarters for AED 505 million; first Middle East member of Forbes Global Properties ([Instagram](https://www.instagram.com/drivenproperties)).
- [Metropolitan Premium Properties](https://metropolitan.realestate) - Dubai agency founded 2012 by Nikita Kuznetsov within the Metropolitan Group (2008); claims 1,000+ brokers and AED 11 billion in group sales in 2022. Strong with developer launches and CIS buyers; first place at the Arada Broker Awards 2025.
- [Provident Estate](https://providentestate.com) - Founded 2008, led by CEO Loai Al Fakir; off-plan and secondary with a large villa team. Property Finder Rent Champion for MBR City 2025 ([Instagram](https://www.instagram.com/providentestate)).
- [Espace Real Estate](https://www.espace.ae) - Founded 2009 to bring UK agency standards to Dubai's villa communities, run by MD John Lyons. Its Joren Huijten was Property Finder's SuperAgent of the Year 2025 ([Instagram](https://www.instagram.com/espacerealestate)).
- [Unique Properties](https://www.uniqueproperties.ae) - Founded 2008, now led by CEO Armin Jalili; more than AED 24 billion in cumulative sales, historically off-plan focused and expanding into secondary ([Instagram](https://www.instagram.com/unique_properties)).
- [Union Square House](https://www.ushre.com) - Founded 2010 by Gaurav Aidasani; 100+ agents, AED 4.5 billion in 2023 sales and a decade of top broker awards from Emaar, Nakheel, Meraas, and Damac ([Instagram](https://www.instagram.com/unionsquarehouse)).
- [AX Capital](https://www.axcapital.ae) - Founded 2018; 500+ staff serving CIS, European, and South Asian buyers, exclusive global sales partner for GFS Developments ([Instagram](https://www.instagram.com/axcapital.uae)).
- [Springfield Properties](https://springfieldproperties.ae) - Founded 2008, run by Farooq Syed, whose YouTube channel is the largest Dubai real estate channel; publishes quarterly DLD-based market reports.
- [Aeon & Trisl](https://aeontrisl.com) - Emaar's number one broker for seven consecutive quarters through Q1 2025.
- [Dubai Sotheby's International Realty](https://sothebysrealty.ae) - Franchise acquired 2013 by George Azar; ultra-prime specialist. 2025 records: AED 330 million Jumeirah Bay villa, AED 365 million Palm Jumeirah plot, AED 161 million Palm villa resale ([Instagram](https://www.instagram.com/dubai_sothebys_realty)).
- [Engel & Völkers Dubai](https://www.engelvoelkers.com/ae/en) - Licence partner of the Hamburg group, led by Middle East CEO Daniel Hadi. H1 2025 transaction volume up 48% and commission income up 40% ([Instagram](https://www.instagram.com/engelvoelkersdubai)).
- [Knight Frank UAE](https://www.knightfrank.ae) - Global advisory firm founded 1896 with eight MENA offices; Property Finder Commercial Brokerage of the Year 2025. Its research counted USD 9.05 billion of USD 10 million-plus Dubai home sales in 2025 ([report](https://www.knightfrank.ae/newsroom/article/2026/1/dubai-us$-10m-resi-sales-q4-2025), [Instagram](https://www.instagram.com/knightfrankuae)).
- [Savills Middle East](https://www.savills.ae) - Entered the region by acquiring Cluttons Middle East in 2018; prime residential, commercial, and consultancy with 100+ residential consultants ([Instagram](https://www.instagram.com/savillsmiddleeast)).
- [Huspy](https://huspy.com) - Founded 2021 by Jad Antoun and Khalid Ashmawy; a tech platform for independent agents rather than a classic brokerage, plus a mortgage arm handling over a quarter of Dubai home financing. Raised USD 59 million Series B in July 2025 ([Instagram](https://www.instagram.com/gohuspy)).

## Agents & Public Faces

Individual brokers who are recognised beyond their own firms, with their public professional profiles. Entrepreneur Middle East published the first ranked [100 Agents list](https://mena.entrepreneur.com/leadership/real-estate-leaders-uae-property-market-resilience-agents-ranked-71-100) in August 2026.

- [Honey Deylami](https://sothebysrealty.ae/agent/hanieh-deylami) - Executive Partner at Dubai Sotheby's, ranked number one on the 2026 Entrepreneur list; AED 26 billion advised over 21 years and the AED 220 million AVA penthouse.
- [Zeina Khoury](https://www.instagram.com/thezeinakhoury/) - Founder and CEO of Zed Capital Real Estate and main cast of Netflix's Dubai Bling, with more than a million Instagram followers.
- [Lewis Allsopp](https://mena.entrepreneur.com/entrepreneurs/100-real-estate-agents-lewis-allsopp-chairman-allsopp-allsopp) - Co-founder and chairman of Allsopp & Allsopp.
- [Darren Murphy](https://www.allsoppandallsopp.com/dubai/about-us/news-videos/1710-the-billion-dirham-broker-how-darren-murphy-surpassed-aed-1-billion-in-property-sales-in-2025) - Allsopp & Allsopp partner for Jumeirah Golf Estates who passed AED 1 billion in 2025 sales and won Property Finder's Top Closer award.
- [Joren Huijten](https://mena.entrepreneur.com/leadership/100-real-estate-agents-joren-huijten-associate-director-espace-real-estate) - Espace associate director and Property Finder SuperAgent of the Year 2025.
- [Farooq Syed](https://mena.entrepreneur.com/leadership/100-real-estate-agents-farooq-syed-ceo-springfield-properties) - CEO of Springfield Properties and host of the largest Dubai real estate YouTube channel.
- [Firas Al Msaddi](https://mena.entrepreneur.com/entrepreneurs/100-real-estate-agents-firas-al-msaddi-founder-and-ceo-fam-properties) - Founder of fäm Properties and co-founder of DXB Interact; author of The Art of Real Estate Investment.
- [Rami Wahood](https://www.instagram.com/fam_rami/) - Partner at fäm Properties and cast member of Million Dollar Listing UAE.
- [Ben Bandari](https://mena.entrepreneur.com/entrepreneurs/100-real-estate-agents-ben-bandari-ceo-benco-real-estate) - Founder of BenCo Real Estate and star and executive producer of Million Dollar Listing UAE; AED 25 billion in career sales.
- [Mohanad Alwadiya](https://www.instagram.com/mohanadalwadiya/) - CEO of Harbor Real Estate, weekly Property Today expert on Dubai Eye 103.8, about one million Instagram followers.
- [Tahir Majithia](https://ae.linkedin.com/in/tahirmajithia) - Managing partner of Prime Capital and host of The Dubai Real Estate Podcast.

## Funds, REITs & Institutional Investors

- [Dubai Residential REIT](https://dubairesidential.ae) - Dubai Holding's residential leasing REIT, listed on DFM in May 2025 after a 26-times oversubscribed IPO that raised AED 2.145 billion; 35,700 units across 21 communities. 2025: net profit AED 1.28 billion, NAV AED 22.05 billion ([results](https://dubairesidential.ae/en/news/dr-reit-delivers-record-aed-1-28-billion-net-profit-in-2025)).
- [Emirates REIT](https://reit.ae) - Founded 2010, listed on Nasdaq Dubai in 2014 as the first REIT on a GCC exchange, managed by Equitativa. 2025: total assets USD 1.25 billion, occupancy 96%, loan-to-value cut to 20%.
- [ENBD REIT](https://www.enbdreit.com) - Emirates NBD's Sharia-compliant REIT listed on Nasdaq Dubai in 2017; portfolio USD 419 million across ten assets, mostly offices, with record 95% occupancy in 2025.
- [Al Mal Capital REIT](https://www.almalcapital.com) - First REIT listed on DFM in 2021, majority-owned by Dubai Investments and focused on education and healthcare assets; portfolio about AED 1.4 billion after buying the NMC Royal Hospital property in 2025.
- [Investment Corporation of Dubai](https://www.icd.gov.ae) - The government's principal investment arm with total assets of AED 1.47 trillion in 2024; anchor shareholder of Emaar and co-owner of ICD Brookfield Place in DIFC.
- [Dubai Holding](https://www.dubaiholding.com) - Manages about AED 500 billion in assets and now owns Nakheel, Meydan, Meraas, and Dubai Properties; partner of Brookfield on Solaya and of Aldar on a 14,000-home joint venture.
- [Brookfield](https://www.brookfield.com) - Developed ICD Brookfield Place, launched a USD 1 billion Gulf residential venture with Lunate in 2025, and in May 2026 began a 480,000 square foot mixed-use project in Dubai Hills with Alshaya Group.
- [Lunate](https://www.lunate.com) - Abu Dhabi asset manager that bought 24.5% of ICD Brookfield Place in 2024 and partners Brookfield on Gulf residential development.

## Mortgages & Financing

- [Mortgage Finder](https://www.mortgagefinder.ae) - Compare rates and check eligibility, owned by Property Finder.
- [Holo](https://www.useholo.com) - Online mortgage platform comparing all UAE banks.
- [Emirates NBD Home Loans](https://www.emiratesnbd.com/en/loans/home-loans) - One of the largest mortgage lenders in Dubai.
- [Mashreq Home Loans](https://www.mashreq.com/en/uae/neo/loans/) - Mortgages for residents and non-residents.
- [ADCB Home Loans](https://www.adcb.com/en/personal/loans/home-loans/) - Includes buyout and non-resident products.
- [HSBC UAE Mortgages](https://www.hsbc.ae/mortgages/) - Popular with expats who bank with HSBC elsewhere.
- [Al Etihad Credit Bureau](https://www.aecb.gov.ae) - Pull your credit report before applying for a mortgage.

## Fractional Investing & Tokenization

DLD's Real Estate Tokenisation Project targets tokenised assets reaching 7% of the market, about AED 60 billion, by 2033.

- [PRYPCO Mint](https://mint.prypco.com) - DLD's tokenised title-deed platform launched May 2025 with VARA oversight on the XRP Ledger; minimum AED 2,000. First listing funded in under 24 hours and the second sold out in under two minutes; more than AED 18.65 million raised from 2,600+ investors by early 2026 ([DLD announcement](https://dubailand.gov.ae/en/news-media/dld-launches-the-mena-s-first-tokenized-real-estate-project-through-the-prypco-mint-platform)).
- [PRYPCO](https://prypco.com) - Founded 2022 by Amira Sajwani; fractional investing, mortgages, and Golden Visa services, backed by General Catalyst in 2025.
- [Stake](https://getstake.com) - DFSA-regulated fractional investing from AED 500; raised a USD 31 million Series B led by Emirates NBD in February 2026 with 230+ funded properties and AED 89 million paid to investors in 2025.
- [SmartCrowd](https://www.smartcrowd.ae) - Founded 2017 by Siddiq Farid and Musfique Ahmed, DFSA-regulated since 2018; 25,000+ users and AED 50 million+ funded across 75+ properties, plus a Flip renovation product.
- [Ctrl Alt](https://ctrl-alt.co) - Tokenisation infrastructure behind PRYPCO Mint, integrated with the DLD registry and partnered with Ripple for custody in 2025.
- [VARA](https://www.vara.ae) - Dubai's virtual assets regulator that oversees tokenized real estate.
- [DFSA](https://www.dfsa.ae) - DIFC regulator licensing crowdfunding and tokenization platforms.

## Renting & Tenancy

- [UAE Housing Guide](https://u.ae/en/information-and-services/housing) - Federal overview of renting, buying, and tenant rights across emirates.
- [Ejari Certificate Download](https://dubailand.gov.ae/en/eservices/download-ejari-certificate/) - Retrieve a copy of a registered tenancy contract.
- [Keyper](https://www.keyper.ae) - Rent now, pay later, and landlord cashflow tools.
- [Rently](https://rently.ae) - Pay annual rent monthly instead of post-dated cheques.

## Short-Term Rentals

- [Holiday Homes Licensing](https://www.visitdubai.com/en/business-in-dubai/business-support/holiday-homes) - Department of Economy and Tourism rules for licensing a unit as a holiday home.
- [Airbnb Dubai](https://www.airbnb.com/dubai-united-arab-emirates/stays) - Largest short-term rental marketplace in the city.
- [Frank Porter](https://www.frankporter.com) - Licensed holiday home operator managing units for owners.
- [GuestReady](https://www.guestready.com) - Short-term rental management with dynamic pricing.
- [AirDNA Dubai](https://www.airdna.co/vacation-rental-data/app/ae/default/dubai/overview) - Occupancy and rate data for short-term rentals.

## Property Management & Services

- [Emaar Community Management](https://www.emaarcommunitymanagement.com) - Owner association portal for Emaar communities.
- [Nakheel Community Management](https://www.nakheelcommunities.com) - Portal for Palm Jumeirah and other Nakheel communities.
- [Empower](https://www.empower.ae) - District cooling provider; chilled water bills are separate from DEWA in many towers.
- [ServiceMarket](https://www.servicemarket.com) - Maintenance, cleaning, and moving services marketplace.
- [Hitches & Glitches](https://www.hitchesglitches.com) - Annual maintenance contracts for villas and apartments.

## Visas for Property Investors

- [Golden Visa for Property Investors](https://u.ae/en/information-and-services/visa-and-emirates-id/residence-visas/golden-visa) - Ten-year residency for property worth AED 2 million or more.
- [DLD Golden Visa Service](https://dubailand.gov.ae/en/eservices/request-for-golden-visa-investor/) - Apply through DLD's dedicated investor channel.
- [Property Investor Visa](https://gdrfad.gov.ae) - Two-year residency route for property above AED 750,000 through GDRFA.

## Laws & Regulations

- [DLD Rules & Regulations](https://dubailand.gov.ae/en/about-dubai-land-department/rules-regulations/) - Full text of the key laws: No. 7 of 2006 (registration and freehold areas), No. 26 of 2007 and No. 33 of 2008 (tenancy), No. 8 of 2007 (escrow), No. 6 of 2019 (jointly owned property), and Decree No. 43 of 2013 (rent increases).
- [UAE Legislation Portal](https://uaelegislation.gov.ae) - Federal laws including the Civil Code and the 2022 personal status reforms affecting inheritance.
- [DIFC Wills Service](https://www.difccourts.ae/difc-courts-wills/services/property-will) - Register a will so non-Muslim property passes under home-country law.

## Market Reports & Research

- [Knight Frank Research](https://www.knightfrank.ae/research) - Dubai residential and prime market reviews.
- [CBRE UAE Research](https://www.cbre.ae/insights) - Quarterly market figures for residential, office, and retail.
- [JLL MENA Research](https://www.jll-mena.com/en/trends-and-insights) - Dubai real estate market overview each quarter.
- [Savills Research](https://www.savills.ae/insight-and-opinion/) - Prime residential index and branded residences reports.
- [ValuStrat Price Index](https://valustrat.com/pages/research) - Monthly index of capital values and rents.
- [Cavendish Maxwell Reports](https://www.cavendishmaxwell.com/research) - Detailed quarterly reports by segment.
- [Property Monitor Insights](https://propertymonitor.com/insights) - Monthly transaction and price index report.
- [UAE Central Bank Statistics](https://www.centralbank.ae/en/our-operations/monetary-management/statistics/) - Mortgage lending and banking data.
- [IMF UAE](https://www.imf.org/en/Countries/ARE) - Macro assessments that often discuss property market risk.
- [Betterhomes Quarterly Reports](https://www.bhomes.com/en/blog/market-reports/shaping-skylines-dubai-residential-real-estate-q3-2025) - Broker-side view of demand, buyer nationalities, and leasing trends.
- [haus & haus Market Reports](https://www.hausandhaus.com/uk/resources/market-reports/dubai-real-estate-market-reports-2025/) - Community-level 2025 reports for villas and apartments.

## News & Media

- [Arabian Business Real Estate](https://www.arabianbusiness.com/industries/real-estate) - Daily coverage of launches, deals, and policy.
- [Gulf News Property](https://gulfnews.com/business/property) - Local property news and buyer advice.
- [Khaleej Times Real Estate](https://www.khaleejtimes.com/business/realty) - Market news and rental guides.
- [The National Property](https://www.thenationalnews.com/business/property/) - In-depth reporting on UAE real estate.
- [Zawya Real Estate](https://www.zawya.com/en/business/real-estate) - Regional financial news on property.
- [Dubai Media Office](https://mediaoffice.ae) - Official announcements, including DLD monthly transaction totals.
- [MyBayut](https://www.bayut.com/mybayut/) - Area guides, buying guides, and market explainers.
- [Property Finder Blog](https://www.propertyfinder.ae/blog) - Guides and news for buyers and tenants.

## Media, Podcasts & Newsletters

- [DXB Interact on X](https://x.com/dxbinteract) - Weekly top sales and transaction snapshots straight from DLD data.
- [The Real Estate Report](https://therealestatereport.substack.com) - Substack newsletter on Dubai transactions and news with 22,000+ subscribers.
- [Dubai Real Estate Unplugged](https://dubairealestateunplugged.buzzsprout.com) - Podcast from haus & haus running since 2021 with about 90 episodes.
- [The Dubai Plug](https://www.buzzsprout.com/1795738) - Data-led monthly market breakdowns by Provident's Alessandro de Rubertis.
- [Property Today on The Agenda](https://dubaieye1038.com/podcasts/property-today-on-the-agenda) - Dubai Eye 103.8 weekly radio segment with Mohanad Alwadiya.
- [Real Estate Club Dubai](https://realestateclubdubai.com) - Independent research site comparing data platforms and ranking brokerages.
- [Dive Dubai](https://dive-dubai.com) - Guides to Dubai and UAE living, diving, and coastal areas that buyers and tenants use when choosing waterfront communities. Maintained by the author of this list.

## Developer Resources

- [DLD Real Estate Data](https://dubailand.gov.ae/en/open-data/real-estate-data/) - CSV exports of transactions, rents, units, buildings, projects, and licensed brokers.
- [Dubai Pulse APIs](https://www.dubaipulse.gov.ae/organisation/dld) - Programmatic access to DLD datasets.
- [Makani](https://www.makani.ae) - Ten-digit geo-address system with an API for mapping units to coordinates.
- [Kaggle Dubai Real Estate Datasets](https://www.kaggle.com/search?q=dubai+real+estate+in%3Adatasets) - Community-uploaded copies of DLD data for modelling.
- [Hugging Face Datasets](https://huggingface.co/datasets?search=dubai) - Dubai property datasets for machine learning.

## Key Numbers

Figures below are the commonly cited rules of thumb as of 2026. Always confirm with DLD or your bank before relying on them.

| Figure        | What it is                                                                                                                            |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 4%            | DLD transfer fee on sale price, usually paid by the buyer, plus an admin fee of AED 580 for apartments and AED 430 for land.          |
| 2%            | Typical brokerage commission on sales, paid by the buyer. Rentals are usually 5% of annual rent.                                      |
| 0.25%         | Mortgage registration fee on the loan amount, plus AED 290.                                                                           |
| 80% / 70%     | Maximum loan-to-value for expats on a first property under or over AED 5 million. UAE nationals get 85% / 75%.                        |
| 50%           | Maximum loan-to-value for off-plan purchases.                                                                                         |
| AED 2,000,000 | Property value required for a Golden Visa.                                                                                            |
| AED 750,000   | Property value required for the two-year Property Investor Visa.                                                                      |
| 90 days       | Notice a landlord must give before expiry to change rent or terms.                                                                    |
| 12 months     | Notarised notice required to evict a tenant for sale or personal use.                                                                 |
| 0% to 20%     | Rent increase allowed on renewal, in 5% steps, depending on how far below the RERA index the current rent sits.                       |
| 5%            | VAT on commercial property; residential sales and leases are exempt, and first supply within three years of completion is zero-rated. |

## Related Lists

- [awesome-real-estate](https://github.com/etewiah/awesome-real-estate) - Global real estate technology and resources.
- [awesome-expat](https://github.com/marceloboeira/awesome-expat) - Resources for moving abroad.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
