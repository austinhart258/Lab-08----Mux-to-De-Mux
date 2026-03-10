# Multiplexers and Demultiplexers

In this lab you have learned about multiplexers and demultiplexers.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Names
Austin Hart & Kellan McCamish
## Summary
In this lab we learned how to create a mux/demux using input and output data, each of our inputs in the mux were 4bit and 'Enable' & 'Sel' were output to Y (4bit). Then we sent the output Y into our Demux which led to input 'Enable' and 'Sel' which fed our output to the LED's mapped to our locations around the 'city'.
## Lab Questions

### In plain English describe the function and use of a multiplexer.
- A multiplexer takes in data and using the Enable and Select we are able to designate our output using formations of equations we created within verilog design. A mux is used to select input data to send through to Y and 'Sel' is used to choose which is displayed/output.
### In plain English describe the function and use of a demultiplexer.
- A demultiplexer takes in output and feeds it back through the demux and 'Sel' selects which output is chosen to display. This is all based on 1 input using select to find displayed output.
### What other uses might these circuits have? (Think Shannon’s)
- The Mux/Demux are able to help simplify logic functions. Mux's can implement any boolean logic function due to a universal selector. This means that Mux's can replace entire banks of logic gates, simplifying verilog design as well as circuit design.
