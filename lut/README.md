# Look-up tables for gsmcodecs

Source: 3GPP TS 23.038 version 18.0.0 Release 18

## Source Files

File | ID | National Language | Type | Section
--- | --- | --- | --- | ---
default_lock.csv | 0x0 | Default | GSM default | 6.2.1
default_shift.csv | 0x0 | Default | Single shift | 6.2.1.1
turkish_lock.csv | 0x1 | Turkish | Locking shift | A.3.1
turkish_shift.csv | 0x1 | Turkish | Single shift | A.2.1
spanish_shift.csv | 0x2 | Spanish | Single shift | A.2.2
portugese_lock.csv | 0x3 | Portugese | Locking shift | A.3.3
portugese_shift.csv | 0x3 | Portugese | Single shift | A.2.3
bengali_lock.csv | 0x4 | Bengali | Locking shift | A.3.4
bengali_shift.csv | 0x4 | Bengali | Single shift | A.2.4
gujarati_lock.csv | 0x5 | Gujarati | Locking shift | A.3.5
gujarati_shift.csv | 0x5 | Gujarati | Single shift | A.2.5
hindi_lock.csv | 0x6 | Hindi | Locking shift | A.3.6
hindi_shift.csv | 0x6 | Hindi | Single shift | A.2.6
kannada_lock.csv | 0x7 | Kannada | Locking shift | A.3.7
kannada_shift.csv | 0x7 | Kannada | Single shift | A.2.7
malayalam_lock.csv | 0x8 | Malayalam | Locking shift | A.3.8
malayalam_shift.csv | 0x8 | Malayalam | Single shift | A.2.8
oriya_lock.csv | 0x9 | Oriya | Locking shift | A.3.9
oriya_shift.csv | 0x9 | Oriya | Single shift | A.2.9
punjabi_lock.csv | 0xa | Punjabi | Locking shift | A.3.10
punjabi_shift.csv | 0xa | Punjabi | Single shift | A.2.10
tamil_lock.csv | 0xb | Tamil | Locking shift | A.3.11
tamil_shift.csv | 0xb | Tamil | Single shift | A.2.11
telugu_lock.csv | 0xc | Telugu | Locking shift | A.3.12
telugu_shift.csv | 0xc | Telugu | Single shift | A.2.12
urdu_lock.csv | 0xd | Urdu | Locking shift | A.3.13
urdu_shift.csv | 0xd | Urdu | Single shift | A.2.13

## Scripts

   - mkcharmaps: Read CSV tables into JSON charmaps file
   - codegen: Create python script with encode and decode charmaps
     for each national language.

