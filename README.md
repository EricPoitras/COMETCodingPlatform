# COMETCodingPlatform

# Databases
1. ModelDatabase (!Add final coded transcript following interrater agreement)
2. TranscriptDatabase (!Add all transcribed and segmented transcripts to the server)
3. CodingSchemeDatabase (!Define SRL and CSCL coding scheme)
4. WordList (Updated in train_Model)

# Server Side Processes
# !Initialize
1. get_Database (Retrieves CodingSchemeDatabase & TranscriptDatabase to populate data in user interface)

# Webservices (API) Calls
2. set_Database (Updates TranscriptDatabase when user clicks on Set to save rater names and codes - URL parameter Query="")
3. apply_Model (Applies model when user clicks on predict to generate recommended code and model probabilities - URL parameter Talk_Turn="")

# Machine Learning Algorithm
1. Classifier (Store Model)
2. train_Model (Train and Evaluate Model)

# Static Dashboard
... To be built later... Graphs and metrics for interrater reliability and descriptive stats
