---
title: HSIP Law Enforcement Locations in New Mexico
created: '2020-12-02T17:23:24.521533'
modified: '2020-12-02T17:23:24.521540'
state: active
type: dataset
tags:
  - Airport Police
  - And Explosives
  - Border Patrols.
  - Campus Police
  - Community Policing.
  - Constables
  - Correctional Institutions.
  - Criminal Investigation.
  - Drug Enforcement Agents
  - Fire Marshals
  - Firearms
  - Indian Reservation Police
  - Jails
  - Juvenile Detention
  - Law Enforcement.
  - Military Police
  - New Mexico
  - Peace Officers
  - Police
  - Police Stations
  - Police.
  - Prisons.
  - Railroad Police
  - School Police
  - Secret Service.
  - Sheriffs
  - State.
  - Tobacco
  - Traffic Police.
  - Transit Police
  - U.s. Customs And Border Protection.
  - U.s. Fish And Wildlife Service.
  - U.s. Immigration And Customs Enforcement.
  - United States Marshals.
  - United States. Bureau Of Alcohol
  - United States. Bureau Of Indian Affairs.
  - United States. Bureau Of Reclamation.
  - United States. National Park Service.
  - Work Camps
groups: []
csv_url: >-
  http://gstore.unm.edu/apps/rgisarchive/datasets/faeb3a73-8c0d-40f2-9d69-6075aa1e108e/2009_12_11_nm_lawenforcement.derived.csv
json_url: >-
  http://gstore.unm.edu/apps/rgisarchive/datasets/faeb3a73-8c0d-40f2-9d69-6075aa1e108e/2009_12_11_nm_lawenforcement.derived.json
layout: post

---

Law Enforcement Locations

Any location where sworn officers of a law enforcement agency are regularly based or stationed. Law Enforcement agencies "are publicly funded and employ at least one full-time or part-time sworn officer with general arrest powers". This is the definition used by the US Department of Justice - Bureau of Justice Statistics (DOJ-BJS) for their Law Enforcement Management and Administrative Statistics (LEMAS) survey. Although LEMAS only includes non Federal Agencies, this dataset includes locations for federal, state, local, and special jurisdiction law enforcement agencies.

Law enforcement agencies include, but are not limited to, municipal police, county sheriffs, state police, school police, park police, railroad police, federal law enforcement agencies, departments within non law enforcement federal agencies charged with law enforcement (e.g., US Postal Inspectors), and cross jurisdictional authorities (e.g., Port Authority Police).

In general, the requirements and training for becoming a sworn law enforcement officer are set by each state. Law Enforcement agencies themselves are not chartered or licensed by their state. County, city, and other government authorities within each state are usually empowered by their state law to setup or disband Law Enforcement agencies. Generally, sworn Law Enforcement officers must report which agency they are employed by to the state.

Although TGS's intention is to only include locations associated with agencies that meet the above definition, TGS has discovered a few locations that are associated with agencies that are not publicly funded. TGS deleted these locations as we became aware of them, but some may still exist in this dataset.

Personal homes, administrative offices, and temporary locations are intended to be excluded from this dataset; however, some personal homes are included due to the fact that the New Mexico Mounted Police work out of their homes.

TGS has made a concerted effort to include all local police; county sheriffs; state police and/or highway patrol; Bureau of Indian Affairs; Bureau of Land Management; Bureau of Reclamation; U.S. Park Police; Bureau of Alcohol, Tobacco, Firearms, and Explosives; U.S. Marshals Service; U.S. Fish and Wildlife Service; National Park Service; U.S. Immigration and Customs Enforcement; and U.S. Customs and Border Protection.

This dataset is comprised completely of license free data.

FBI entities are intended to be excluded from this dataset, but a few may be included.

The Law Enforcement dataset and the Correctional Institutions dataset were merged into one working file. TGS processed as one file and then separated for delivery purposes.

With the merge of the Law Enforcement and the Correctional Institutions datasets, the NAICS Codes & Descriptions were assigned based on the facility's main function which was determined by the entity's name, facility type, web research, and state supplied data. In instances where the entity's primary function is both law enforcement and corrections, the NAICS Codes and Descriptions are assigned based on the dataset in which the record is located (i.e., a facility that serves as both a Sheriff's Office and as a jail is designated as [NAICSDESCR]="SHERIFFS' OFFICES (EXCEPT COURT FUNCTIONS ONLY)" in the Law Enforcement layer and as [NAICSDESCR]="JAILS (EXCEPT PRIVATE OPERATION OF)" in the Correctional Institutions layer).

Records with "-DOD" appended to the end of the [NAME] value are located on a military base, as defined by the Defense Installation Spatial Data Infrastructure (DISDI) military installations and military range boundaries.

"#" and "*" characters were automatically removed from standard fields that TGS populated. Double spaces were replaced by single spaces in these same fields.

Text fields in this dataset have been set to all upper case to facilitate consistent database engine search results.

All diacritics (e.g., the German umlaut or the Spanish tilde) have been replaced with their closest equivalent English character to facilitate use with database systems that may not support diacritics. 

The currentness of this dataset is indicated by the [CONTDATE] field. Based on the values in this field, the oldest record dates from 08/14/2006 and the newest record dates from 10/23/2009

