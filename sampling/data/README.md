Data
===

Response (response.csv)
---

The responses from all the participants are organized in one csv file. Below
are the column names along with the description.

- **participant** Integer. ID to index the participants.

- **phase** String. Either "training", "long" or "short". The latter two
  represent the long-rt and short-rt testing phases.

- **trial** Integer. The trial number.

- **practice** String. The practice trials are indicated as "yes" in this
  column.

- **stimulusId** Integer. ID to index the stimuli.

- **length** Float. The lengths of presented stimuli before being converted
  into pixels. See the description of experiment for more information.

- **pixelLength** String. The lengths of stimuli in pixel.

- **category** Integer. The stimuli categories.

- **judgedCategory** Integer. The category judgements made by the participants.

- **responseTime** Integer. The time taken for the participants to press a key
  in milliseconds.


Demographic (demographic.csv)
---

The age and gender of participants are organized in this csv file. The
"participant" column can be used to merge with the above response.csv.
