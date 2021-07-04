# FindSpamMail

<b>Work Assignment</b>

Create a classifier of SPAM using Bayes theorem. Investigate a dependency between classifier parameters and efficiency of the classifier output.

<b>Program Code</b>

perc20.py - Arrange Files for Testing & Training

train.ipynb - Remove HTML, Find Lexemes, Find Spamicity Probability for Training Data and save them as a json file.

test.ipynb - Finding the probability that an email is spam using json files.

<b>Dependency Chart</b>

N = Number of analyzed lexemes

SV = Spamicity value of unseen lexeme

Threshold = Threshold Spamicity Value

SH = Number of SPAM files classified as HAM

HS = Number of HAM files classified as SPAM

SS = Number of SPAM files classified as SPAM

HH = Number of HAM files classified as HAM


Respectively - Index,	N, SV, Threshold, HS, SH, SS, HH, Accuracy

1.		8	  0.4	0.5	6	31	245	582	0.957
2.		16	0.4	0.5	6	27	249	582	0.962
3.		24	0.4	0.5	5	27	249	583	0.963
4.		32	0.4	0.5	5	29	247	583	0.960
5.		8   0.5	0.5	6	31	245	582	0.957
6.		16	0.5	0.5	6	27	249	582	0.962
7.		24	0.5	0.5	5	27	249	583	0.963
8.		32	0.5	0.5	5	28	248	583	0.962
9.		8	  0.6	0.5	7	31	245	581	0.956
10.		16	0.6	0.5	7	26	250	581	0.962
11.		24	0.6	0.5	6	25	251	582	0.964
12.		32	0.6	0.5	6	27	249	582	0.962
13.		8	  0.7	0.5	7	30	246	581	0.957
14.		16	0.7	0.5	7	24	252	581	0.964
15.		24	0.7	0.5	6	22	254	582	0.968
16.		32	0.7	0.5	6	23	253	582	0.966
17.		8	  0.4	0.6	4	35	241	584	0.955
18.		16	0.4	0.6	2	29	247	586	0.964
19.		24	0.4	0.6	4	27	249	584	0.964
20.		32	0.4	0.6	4	31	245	584	0.959
21.		8	  0.5	0.6	4	36	240	584	0.954
22.		16	0.5	0.6	2	29	247	586	0.964
23.		24	0.5	0.6	4	27	249	584	0.964
24.		32	0.5	0.6	4	30	246	584	0.961
25.		8	  0.6	0.6	4	35	241	584	0.955
26.		16	0.6	0.6	2	27	249	586	0.966
27.		24	0.6	0.6	4	26	250	584	0.965
28.		32	0.6	0.6	4	29	247	584	0.962
29.		8	  0.7	0.6	5	33	243	583	0.956
30.		16	0.7	0.6	3	24	252	585	0.969
31.		24	0.7	0.6	5	23	253	583	0.968
32.		32	0.7	0.6	5	27	249	583	0.963
33.		8	  0.4	0.7	4	36	240	584	0.954
34.		16	0.4	0.7	2	30	246	586	0.963
35.		24	0.4	0.7	4	28	248	584	0.963
36.		32	0.4	0.7	4	33	243	584	0.957
37.		8	  0.5	0.7	4	36	240	584	0.954
38.		16	0.5	0.7	2	30	248	586	0.963
39.		24	0.5	0.7	4	28	248	584	0.963
40.		32	0.5	0.7	4	31	245	584	0.959
41.		8  	0.6	0.7	4	36	240	584	0.954
42.		16	0.6	0.7	2	30	248	586	0.963
43.		24	0.6	0.7	4	27	249	584	0.964
44.		32	0.6	0.7	4	30	246	584	0.960
45.		8	  0.7	0.7	4	36	240	584	0.954
46.		16	0.7	0.7	2	30	248	586	0.963
47.		24	0.7	0.7	4	27	249	584	0.964
48.		32	0.7	0.7	4	30	246	584	0.961
49.		8	  0.4	0.8	4	67	209	584	0.918
50.		16	0.4	0.8	2	44	232	586	0.947
51.		24	0.4	0.8	4	38	238	584	0.951
52.		32	0.4	0.8	4	39	237	584	0.950
53.		8	  0.5	0.8	4	67	209	584	0.918
54.		16	0.5	0.8	2	44	232	586	0.947
55.		24	0.5	0.8	4	38	238	584	0.951
56.		32	0.5	0.8	4	37	239	584	0.953
57.		8	  0.6	0.8	4	67	209	584	0.918
58.		16	0.6	0.8	2	44	232	586	0.947
59.		24	0.6	0.8	4	38	238	584	0.951
60.		32	0.6	0.8	4	37	239	584	0.953
61.		8	  0.7	0.8	4	67	209	584	0.918
62.		16	0.7	0.8	2	44	232	586	0.947
63.		24	0.7	0.8	4	38	238	584	0.951
64.		32	0.7	0.8	4	37	239	584	0.953

