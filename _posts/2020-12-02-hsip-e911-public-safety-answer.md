---
title: HSIP E911 Public Safety Answering Point (PSAP)
created: '2020-12-02T16:53:42.953883'
modified: '2020-12-02T16:53:42.953890'
state: active
type: dataset
tags:
  - Boundaries
  - New Mexico
  - Telephone Emergency Reporting Systems
groups: []
csv_url: >-
  http://gstore.unm.edu/apps/rgisarchive/datasets/c3e6f7a7-df4a-4954-9264-5fbedcdb63e0/2008_04_09_nm_911_psap.derived.csv
json_url: >-
  http://gstore.unm.edu/apps/rgisarchive/datasets/c3e6f7a7-df4a-4954-9264-5fbedcdb63e0/2008_04_09_nm_911_psap.derived.json
layout: post

---
 911 Public Safety Answering Point (PSAP) service area boundaries in New
                Mexico According to the National Emergency Number Association (NENA), a Public
                Safety Answering Point (PSAP) is a facility equipped and staffed to receive 9-1-1
                calls. The service area is the geographic area within which a 911 call placed using
                a landline is answered at the associated PSAP. This dataset only includes primary
                PSAPs. Secondary PSAPs, backup PSAPs, and wireless PSAPs have been excluded from
                this dataset. Primary PSAPs receive calls directly, whereas secondary PSAPs receive
                calls that have been transferred by a primary PSAP. Backup PSAPs provide service in
                cases where another PSAP is inoperable. Most military bases have their own emergency
                telephone systems. To connect to such system from within a military base it may be
                necessary to dial a number other than 9 1 1. Due to the sensitive nature of military
                installations, TGS did not actively research these systems. If civilian authorities
                in surrounding areas volunteered information about these systems or if adding a
                military PSAP was necessary to fill a hole in civilian provided data, TGS included
                it in this dataset. Otherwise military installations are depicted as being covered
                by one or more adjoining civilian emergency telephone systems. In some cases areas
                are covered by more than one PSAP boundary. In these cases, any of the applicable
                PSAPs may take a 911 call. Where a specific call is routed may depend on how busy
                the applicable PSAPS are (i.e. load balancing), operational status (i.e.
                redundancy), or time of date / day of week. If an area does not have 911 service,
                TGS included that area in the dataset along with the address and phone number of
                their dispatch center. These are areas where someone must dial a 7 or 10 digit
                number to get emergency services. These records can be identified by a "Y" in the
                [NON911EMNO] field. This indicates that dialing 911 inside one of these areas does
                not connect one with emergency services. This dataset was constructed by gathering
                information about PSAPs from state level officials. In some cases this was
                geospatial information, in others it was tabular. This information was supplemented
                with a list of PSAPs from the Federal Communications Commission (FCC). Each PSAP was
                researched to verify its tabular information. In cases where the source data was not
                geospatial, each PSAP was researched to determine its service area in terms of
                existing boundaries (e.g. city and county boundaries). In some cases existing
                boundaries had to be modified to reflect coverage areas (e.g. "entire county north
                of Country Road 30"). However, there may be cases where minor deviations from
                existing boundaries are not reflected in this dataset, such as the case where a
                particular PSAPs coverage area includes an entire county, and the homes and
                businesses along a road which is partly in another county. Text fields in this
                dataset have been set to all upper case to facilitate consistent database engine
                search results. All diacritics (e.g., the German umlaut or the Spanish tilde) have
                been replaced with their closest equivalent English character to facilitate use with
                database systems that may not support diacritics. 
