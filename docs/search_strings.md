# Search strings

Searches run for records published January 2015 – 15 September 2026; exports downloaded 10 October 2026. See Appendix A of the manuscript and `data/00_prisma_counts.csv` for records retrieved per source.

## IEEE Xplore
Command Search, All Metadata; conferences, journals, early access

```
("large language model" OR "large language models" OR LLM OR LLMs OR "vision language model" OR "vision-language model" OR "multimodal large language model" OR MLLM OR GPT OR ChatGPT OR "foundation model" OR agentic OR "AI agent" OR "LLM agent" OR "LLM-based agent" OR "autonomous agent" OR "multi-agent") AND ("software testing" OR "GUI testing" OR "UI testing" OR "web testing" OR "web application testing" OR "app testing" OR "mobile testing" OR "Android testing" OR "end-to-end testing" OR "E2E testing" OR "exploratory testing" OR "acceptance testing" OR "functional testing" OR "system testing" OR "test automation" OR "automated testing" OR "test oracle" OR "test execution" OR "bug detection" OR "defect detection" OR "functional bug" OR tester) AND (GUI OR "user interface" OR web OR browser OR mobile OR Android OR iOS OR app OR apps OR "end-to-end" OR E2E OR exploratory OR acceptance OR "system under test")
```

## ACM Digital Library
Advanced Search, ACM Full-Text Collection, field Abstract

```
Abstract:("large language model*" OR LLM* OR "vision language model*" OR "vision-language model*" OR "multimodal large language model*" OR MLLM* OR GPT* OR ChatGPT OR "foundation model*" OR agentic OR "AI agent*" OR "LLM-based agent*" OR "autonomous agent*" OR "multi-agent") AND Abstract:("software test*" OR "GUI test*" OR "UI test*" OR "web test*" OR "app test*" OR "mobile test*" OR "Android test*" OR "end-to-end test*" OR "E2E test*" OR "exploratory test*" OR "acceptance test*" OR "functional test*" OR "system test*" OR "test automation" OR "automated test*" OR "test oracle*" OR "test execution" OR "bug detection" OR "defect detection" OR "functional bug*" OR tester*) AND Abstract:(GUI OR "graphical user interface*" OR "user interface*" OR web OR browser OR mobile OR Android OR iOS OR app OR apps OR "end-to-end" OR E2E OR exploratory OR acceptance OR "system under test")
```

## ScienceDirect
field Title, abstract or author-specified keywords; four queries, because the field accepts at most eight Boolean connectors

```
Q1: ("large language model" OR LLM OR GPT OR "AI agent" OR agentic) AND ("GUI testing" OR "UI testing" OR "web testing" OR "mobile app testing")
Q2: ("large language model" OR LLM OR GPT OR "AI agent" OR agentic) AND ("end-to-end testing" OR "exploratory testing" OR "acceptance testing" OR "functional testing")
Q3: ("large language model" OR LLM OR GPT OR "AI agent" OR agentic) AND ("software testing" OR "test automation" OR "automated testing" OR "test oracle")
Q4: ("large language model" OR LLM OR GPT OR "AI agent" OR agentic) AND ("Android testing" OR "system testing" OR "bug detection" OR "defect detection")
```

## Wiley Online Library and Taylor & Francis Online
Advanced Search, three rows joined by AND

```
Row 1: "large language model*" OR LLM* OR "vision language model*" OR GPT* OR ChatGPT OR agentic OR "AI agent*" OR "autonomous agent*" OR "multi-agent"
Row 2: "software test*" OR "GUI test*" OR "web test*" OR "mobile test*" OR "end-to-end test*" OR "exploratory test*" OR "acceptance test*" OR "functional test*" OR "test oracle*" OR "test automation"
Row 3: GUI OR "user interface*" OR web OR browser OR mobile OR Android OR app OR apps OR "end-to-end" OR exploratory OR acceptance
```

## SpringerLink
full-text search; articles and conference papers; Computer Science

```
("large language model" OR "large language models" OR LLM OR "vision language model" OR GPT OR agentic OR "AI agent" OR "LLM agent" OR "autonomous agent") AND ("GUI testing" OR "web testing" OR "mobile app testing" OR "Android testing" OR "end-to-end testing" OR "exploratory testing" OR "acceptance testing" OR "functional testing" OR "test oracle" OR "test automation")
```

## arXiv
API, all fields; submitted 1 January 2015 to 15 September 2026

```
(all:"large language model" OR all:LLM OR all:"vision language model" OR all:GPT OR all:agentic OR all:"AI agent" OR all:"LLM agent" OR all:"multi-agent") AND (all:"GUI testing" OR all:"web testing" OR all:"app testing" OR all:"mobile testing" OR all:"end-to-end testing" OR all:"exploratory testing" OR all:"acceptance testing" OR all:"functional testing" OR all:"software testing" OR all:"test automation" OR all:"test oracle" OR all:"bug detection") AND submittedDate:[201501010000 TO 202609152359]
```
