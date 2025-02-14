# Chapter 6 - Series

> **AP Exam Weight**: 15-25% | Multiple Choice: 6-10 questions | Free Response: Usually 1 full question

## 📚 Table of Contents
1. [Sequence Basics]
2. [Series Tests]
3. [Power Series]
4. [Taylor Series]
5. [Error Bounds]

## 1. Sequence Basics 📊

### Understanding Sequences
A sequence is a list of numbers in order. Think of it as:
- Pattern of values following a rule
- Function with domain of natural numbers
- Stepping stones to series
- Ordered list of terms

### Basic Concepts
#### Notation
- {aₙ} represents a sequence
- aₙ is the nth term
- Explicit vs. recursive form
- Index notation

#### Example Walkthrough
Find the first 4 terms of aₙ = n²/(n+1)
1. **n = 1**:
   - a₁ = 1²/(1+1) = 1/2
2. **n = 2**:
   - a₂ = 2²/(2+1) = 4/3
3. **n = 3**:
   - a₃ = 9/4
4. **n = 4**:
   - a₄ = 16/5

### Convergence of Sequences
#### Process for Finding Limits
1. **Identify Pattern**:
   - Look for trend
   - Consider behavior as n grows
   - Watch for special forms
   - Consider asymptotes

2. **Calculate Limit**:
   - Use limit techniques
   - Consider infinity rules
   - Watch for indeterminate forms
   - Verify conclusion

#### Example Walkthrough
Find $\lim_{n \to \infty} \frac{n+1}{n}$
1. **Analyze form**:
   - Divide numerator and denominator by n
2. **Simplify**:
   - $\lim_{n \to \infty} (1 + \frac{1}{n})$
3. **Evaluate**:
   - As n → ∞, 1/n → 0
   - Limit = 1

### Common Mistakes
1. **Notation Errors**:
   - Confusing n and k
   - Missing subscripts
   - Wrong index bounds
   - Incorrect brackets/parentheses

2. **Conceptual Errors**:
   - Confusing sequence vs. series
   - Wrong starting index
   - Missing terms
   - Pattern recognition

## 2. Series Tests 🔍

### Understanding Series
A series is the sum of sequence terms. Think of it as:
- Adding up infinite terms
- Accumulation of sequence values
- Limit of partial sums
- Infinite summation

### Test Selection Guide
| Test | When to Use |
|------|-------------|
| n-th Term | First check |
| Geometric | Constant ratio |
| p-Series | $\frac{1}{n^p}$ form |
| Integral | Decreasing, positive |
| Comparison | Compare to known |
| Ratio | Fraction of terms |
| Root | nth root |
| Alternating | (-1)ⁿ series |

### Detailed Tests
#### 1. n-th Term Test
- If $\lim_{n \to \infty} a_n \neq 0$, series diverges
- Necessary but not sufficient
- Quick first check
- Can't prove convergence

---

*💡 Pro Tip: Memorize common Taylor series and their intervals of convergence - they're frequently tested!* 
