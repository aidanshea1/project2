# Large Scale Data Processing: Project 2
# Aidan Shea
# Results

## Exact F0
### Running locally:
##### Time Elapsed: 92 seconds
##### Estimate: 7406649
### Running on GCP:
##### Time Elapsed: 76 seconds
##### Estimate: 7406649

## Exact F2
### Running locally: 
#### Time Elapsed: 101 seconds
#### Estimate: 4272998834
### Running on GCP:
##### Time Elapsed: 82 seconds
##### Estimate: 4272998834

## Tug Of War F2 Approximation
### Running locally: 
##### Width: 10
##### Depth: 3
##### Time Elapsed: 107 seconds
##### Estimate: 6878545630
### Running on GCP:
##### Width: 10
##### Depth: 3
##### Time Elapsed: 147 seconds
##### Estimate: 4631727400

## BJKST Algorithm for Distinct Elements
### Running locally:
##### Bucket Size: 100
##### Trials: 50
##### Time Elapsed: 263 seconds
##### Estimate: 8388608.0
### Running on GCP:
##### Bucket Size: 100
##### Trials: 50
##### Time Elapsed: 318 seconds 
##### Estimate: 7471104.0

## BJKST Algorthim vs. Exact F0
##### The BJKST Algorithm with a bucket size of 100 and with 50 trials outputted an estimation within 15% of the exact F0 value when run locally and within 1% of the exact F0 value when run on GDP. However with these values for the bucket size and the number of trials, the BJKST algorithm took longer than the exactF0 program to run. 

## Tug of War F2 Approximation vs. Exact F2
##### The Tug of War F2 Approximation estimate different from the exact F2. When run locally the estimate was around 60% higher than the exact F2 value and when run on GCP the estimate was around 8% higher than the exact F2 value. The Tug of War Algorithm also took longer to run both locally and on GCP.
