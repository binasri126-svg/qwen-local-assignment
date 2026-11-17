Day 5 - Running a Local AI Model Using Ollama

1. Objective

The objective of this assignment is to install and run a local AI model using Ollama, test its ability to solve mathematical calculations, and compare the results of two runs using the same prompt.

2. Tools and Technologies Used

- Ollama
- Qwen 2.5:3B
- Windows Operating System

3. Model Details

| Detail | Information |
|:---|:---|
| Model Name | Qwen 2.5:3B |
| Model Size | Approximately 1.9 GB |
| Platform | Ollama |
| Response Time | Approximately 10 seconds per run |

4. Task Performed

The following prompt was used to test the model's mathematical accuracy:

```text
Solve the following five calculations.
Show only the final answers in a numbered list.

1. 25 + 35
2. 100 - 47
3. 12 * 8
4. 144 / 12
5. 15 * 6
```

5. First Run

The model generated the following answers:

| No. | Calculation | Model Answer | Verification |
|:---:|:---|:---:|:---:|
| 1 | 25 + 35 | 60 | Correct |
| 2 | 100 - 47 | 53 | Correct |
| 3 | 12 * 8 | 96 | Correct |
| 4 | 144 / 12 | 12 | Correct |
| 5 | 15 * 6 | 90 | Correct |

Result: 5 out of 5 calculations were correct.

6. Second Run

The exact same prompt was submitted again to check the consistency of the model.

| No. | Calculation | Model Answer | Verification |
|:---:|:---|:---:|:---:|
| 1 | 25 + 35 | 60 | Correct |
| 2 | 100 - 47 | 53 | Correct |
| 3 | 12 * 8 | 96 | Correct |
| 4 | 144 / 12 | 12 | Correct |
| 5 | 15 * 6 | 90 | Correct |

Result: 5 out of 5 calculations were correct.

7. Comparison and Verification

| Calculation | First Run | Second Run | Result |
|:---|:---:|:---:|:---:|
| 25 + 35 | 60 | 60 | Identical |
| 100 - 47 | 53 | 53 | Identical |
| 12 * 8 | 96 | 96 | Identical |
| 144 / 12 | 12 | 12 | Identical |
| 15 * 6 | 90 | 90 | Identical |

All answers were manually verified. Both runs produced identical and accurate results.

8. Findings

The Qwen 2.5:3B model successfully completed all five mathematical calculations. It provided correct answers in both runs, with an approximate response time of 10 seconds per run.

This experiment helped me understand how to run a local AI model using Ollama, test its responses, manually verify the results, and compare the consistency of its outputs.

9. Conclusion

The assignment was completed successfully using Qwen 2.5:3B through Ollama. The model answered all five calculations correctly in both runs and produced identical results.

10. Screenshot

The screenshot of the Ollama session containing the prompt and model responses is included in this repository.

Screenshot file: quen_test_ss.png

---

Assignment: Week 1 - Day 5  
Topic: Running a Local AI Model  
Model: Qwen 2.5:3B  
Status: Completed
