# Cold Chain Equipment (CCE) & Temperature Monitoring use case

## DHIS2 demo instance
https://lmis.im.dhis2.org/cce/
user: demo
pass: Stock123! 

### Data collection
Use EMS-app, from the top-right menu bar to upload Fridge tag or CCE data to the Cold Chain

### Data Visualization
- navigate through Dashboards, on the top left of the landing page
- Focus on the following dashboards:
1. CCE/EMS - Temperature and performance dashboard - **Health facility level**
* selected visualizations intended for use at a health facility. Target user is the facility manager and other staff who need this data for decision making or reporting
2. CCE/EMS - Temperature and performance dashboard - **Visualisation library**
* Reference visualizations intended to serve as a reference for all user groups to build their own dashboards.

## Key References
* UNICEF Strengthening Data Use for Cold Chain Performance Monitoring - https://www.technet-21.org/en/resources/guidance/cold-chain-temperature-data-job-aid 
* Technology guide for Cold Chain Equipment and Temperature Monitoring: https://www.gavi.org/sites/default/files/support/guidelines-2026/Cold-Chain-Equipment-Programme-and-Technology-Guide_ENG.pdf
* Cold Chain Temperature Data job aid: https://www.technet-21.org/en/resources/guidance/cold-chain-temperature-data-job-aid
* 3-minute overview of the EMS standard: https://docs.2to8.cc/ems-intro/assets/EMS_Overview.mp4 
* References by topic: https://www.technet-21.org/en/topics/supply-chain-and-logistics/ems 

## Raw data
See the /data folder in this repository for the data files from the following appliances/device:
1. B-medical vaccine fridge (EMS standard data format)
2. Vestfrost vaccine fridge (EMS standard data format)
3. Fridge-tag temperature monitor


## Cold chain equipment data use
- UNICEF (2025), Strengthening data use for cold chain performance monitoring: https://storage.googleapis.com/download/storage/v1/b/technet-media/o/media%2Fcom_khub%2Fuploaded%2F17407%2F250709-UNICEF-Cold-Chain-Performance-Monitoring-QRG-Digital_FINAL.pdf?alt=media
- UNICEF (2026), Preparing for the rollout of WHO PQS Equipment Monitoring Systems: https://storage.googleapis.com/download/storage/v1/b/technet-media/o/media%2Fcom_khub%2Fuploaded%2F19615%2FUNICEF%20Country%20Guidance%20-%20Preparing%20for%20the%20roll-out%20of%20WHO%20PQS%20EMS_August%202026.pdf?generation=1790690459125563&alt=media
- CCE Data Interoperability Technical Reference (August 2024), guide for countries and Gavi partners on cold chain equipment data visibility and use: https://www.technet-21.org/media/com_groupresources/uploads/809/CCE%20Data%20Interoperability%20Technical%20Reference%20Document%20Ver%202.pdf
- Gavi (2026), Cold Chain Equipment Programme and Technology Guide: https://www.gavi.org/sites/default/files/support/guidelines-2026/Cold-Chain-Equipment-Programme-and-Technology-Guide_ENG.pdf

### Vaccine temperature monitoring data use
- WHO and UNICEF (2015), How to monitor temperatures in the vaccine supply chain (WHO/IVB/15.04): https://www.who.int/publications/i/item/WHO-IVB-15.04
  - PDF: https://iris.who.int/server/api/core/bitstreams/87e73054-8634-4c32-b7a4-783ef105be19/content
- WHO (2022), How to temperature map cold chain equipment and storage areas (second edition): https://www.who.int/publications/i/item/9789240042773
  - PDF: https://iris.who.int/server/api/core/bitstreams/9c867f76-7a70-452f-85cb-502dc2d36d89/content
- WHO (2018), Temperature monitoring study: a fully documented process to detect weaknesses in the supply chain (WHO/IVB/18.04): https://www.who.int/publications/i/item/WHO-IVB-18.04
  - PDF: https://iris.who.int/server/api/core/bitstreams/f50c915e-afcc-4f8b-8684-011c5de81f6d/content
- WHO (2011), Study protocol for temperature monitoring in the vaccine cold chain (WHO/IVB/05.01 Rev.1): https://www.who.int/publications/i/item/WHO_IVB_05.01_REV.1
- UNICEF, Remote temperature monitoring implementation guide: https://storage.googleapis.com/technet-media/media/com_khub/uploaded/4157%2FRTM%20Implementation%20guide.pdf?alt=media
- WHO, Model Effective Vaccine Management standard operating procedures: https://www.who.int/publications/m/item/model-evm-sop-manual

## Exahustive References
1. WHO Equipment Monitoring System (EMS) — PQS performance specifications for cold chain equipment monitoring
   - Category overview: https://extranet.who.int/prequal/immunization-devices/e006-temperature-monitoring-devices
   - Performance specifications catalogue: https://extranet.who.int/prequal/immunization-devices/performance-specifications
   - Introduction to the PQS Equipment Monitoring System: https://extranet.who.int/prequal/sites/default/files/document_files/Introduction%20to%20the%20PQS%20Equipment%20Monitoring%20System.pdf
   - EMS frequently asked questions: https://extranet.who.int/prequal/sites/default/files/document_files/EMS%20Frequently%20Asked%20Questions.pdf
   - WHO/PQS/E006/DS01.2 — Data standards for cold chain equipment monitoring: https://extranet.who.int/prequal/sites/default/files/document_files/PQS%20E006%20DS01.2_0.pdf
   - WHO/PQS/E006/DS01.2 Annex 1 — Cold chain data objects: https://extranet.who.int/prequal/sites/default/files/document_files/pqs-e006-ds01.2-annex-1-cold-chain-data-objects.xlsx
   - WHO/PQS/E006/DS01.2 Annex 2 — JSON schema: https://extranet.who.int/prequal/sites/default/files/document_files/pqs-e006-ds01.2-annex-2-json-schema.json_.zip
   - WHO/PQS/E006/DL01.3 — Data logger and machine-to-machine interface for Equipment Monitoring Systems: https://extranet.who.int/prequal/sites/default/files/document_files/PQS%20E006%20DL01.3_0.pdf
   - WHO/PQS/E006/EM01.2 — Equipment monitoring devices for Equipment Monitoring Systems: https://extranet.who.int/prequal/sites/default/files/document_files/PQS%20E006%20EM01.2_0.pdf
2. Fridge-tag temperature monitor (Berlinger / Sensitech)
   - Product page: https://www.sensitech.com/en/products/monitors/fridge-tag/
   - Fridge-tag family brochure: https://www.shareddocs.com/hvac/docs/2000/Public/04/fridge-tag-family-brochure.pdf
   - Fridge-tag 2 / 2E user manual: https://www.shareddocs.com/hvac/docs/2000/Public/0B/fridge-tag-2-2e-user-guide.pdf
   - Fridge-tag 2L user manual (external temperature sensor): https://www.shareddocs.com/hvac/docs/2000/Public/0B/fridge-tag-2l-user-guide.pdf
   - WHO PQS E006-020 — Fridge-tag 2: https://extranet.who.int/prequal/immunization-devices/e006-020
   - WHO PQS product record (PDF): https://extranet.who.int/prequal/sites/default/files/immunization_devices/pdf/e006/E006-020.pdf
   - WHO PQS E006-040 — Fridge-tag 2 E: https://extranet.who.int/prequal/immunization-devices/e006-040
   - WHO PQS product record (PDF): https://extranet.who.int/prequal/sites/default/files/immunization_devices/pdf/e006/E006-040.pdf
3. B Medical Systems TCW 40C AC — vaccine refrigerator and water-pack freezer
   - Product page: https://www.bmedicalsystems.com/en/product/tcw40cac/
   - Vaccine Cold Chain brochure: https://www.bmedicalsystems.com/en/wp-content/uploads/sites/2/2026/07/BR_LUX_VCC-NEO__EN_ED072026.pdf
   - User manuals: https://drive.google.com/drive/folders/1V_ZPR3yKAtEguaJ87UkKqKSYV0f5Pi7-?usp=drive_link
   - WHO PQS E003-170: https://extranet.who.int/prequal/immunization-devices/e003-170
   - WHO PQS product record (PDF): https://extranet.who.int/prequal/sites/default/files/immunization_devices/pdf/e003/E003-170.pdf
4. Vestfrost VLS 174A AC — ice-lined vaccine refrigerator (current PQS name: VLS 174Ae AC)
   - Product page: https://www.vestfrostsolutions.com/vaccine-cold-chain/ac-vaccine-refrigerators/vls-174ae-ac/
   - Datasheet: https://www.vestfrostsolutions.com/media/dewhh2dc/vls-174ae-ac-datasheet-2026-english-v-2.pdf
   - User manual: https://www.vestfrostsolutions.com/media/012pmpwn/vls-174ae-trueblue-user-manual-8061015-01.pdf
   - Technical manual: https://www.vestfrostsolutions.com/media/1fodeu15/vls-174ae-ac-trueblue-technical-manual-8195178-01.pdf
   - WHO PQS E003-120e: https://extranet.who.int/prequal/immunization-devices/e003-120e
   - WHO PQS product record (PDF): https://extranet.who.int/prequal/sites/default/files/immunization_devices/pdf/e003/E003-120e.pdf