# Region_Proposal_Network

small mistake in the code, should not effect the result:

```python
diff_t = diff_t = X_reg[k,i,j] - gt_reg[k,i,j]
```

Under the totalLoss function.