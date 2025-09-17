<style>
    .glow-text {
    animation: glow 1.5s ease-in-out infinite alternate;
    font-weight: bold;
    display: inline-block;
}

@keyframes glow {
    from {
        color: #ff6b6b;
        text-shadow: 0 0 2px #ff6b6b, 0 0 4px #ff6b6b, 0 0 6px #ff6b6b;
    }
    to {
        color: #4ecdc4;
        text-shadow: 0 0 3px #4ecdc4, 0 0 6px #4ecdc4, 0 0 9px #4ecdc4;
    }
}

.hard-qn{
    color: rgba(235, 95, 40, 1);
    font-weight: bolder;
    font-style: oblique;
    background-color: bisque;
    width: fit-content;
    padding: 5px;
    border-radius: 10px;
}

</style>

## Amity University Durga Puja Special Offer Suggestions
---
<div align="center" style="margin: 32px 0; padding: 24px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 20px; box-shadow: 0 8px 32px rgba(0,0,0,0.12);">
    <div style="background: white; padding: 20px; border-radius: 16px; display: inline-block; box-shadow: 0 4px 20px rgba(0,0,0,0.1);">
        <img src="amity-durga.png" alt="Amity University Logo" style="max-width: 200px; height: auto; border-radius: 12px; border: 3px solid #f8f9fa; box-shadow: 0 4px 16px rgba(0,0,0,0.08); transition: transform 0.3s ease;" />
    </div>
    <h3 style="color: white; margin-top: 16px; font-family: 'Arial', sans-serif; text-shadow: 0 2px 4px rgba(0,0,0,0.3);">🎉 Durga Puja Special Offer 🎉</h3>
</div>

### Linear Algebra Suggestions:

**Broad Questions:**

1. <span class="glow-text">Important</span> Prove that the following on $\mathbb{R}^n$ defined by $<a,b>=\sum_i^n a_ib_i$ where $a=(a_1,\cdots,a_n)$ and $b=(b_1,\cdots,b_n)$ is a inner product.
2. <span class="hard-qn"> Hard</span> Let $(\mathcal{R}[0,1],\mathbb{R},\int)$ be the set of Riemann integrable functions on $[0,1]$. Prove that $(\mathcal{R}[0,1],\mathbb{R},\int)$ is a vector space and the following 
$$<f,g>=\int_0^1f(x)g(x)dx$$ is a inner product.

3. Extend the set of vectors $\{(1,0,1),(2025,0,2025)\}$to a basis of $\mathbb{R}^3$.
4. State and prove Cauchy-Schwartz Inequality. Also prove that why linearly dependent condition is equivalent to equality.
5. Prove that set of non-zero orthogonal vectors are linearly independent. Is the converse true?
6. What is a set of orthonormal vectors? Let $\{v_1,\cdots, v_n\}$ be a set of non-zero orthogonal vectors. Make it a set of orthonormal vectors easily.
7. Prove that $\forall v\in V$, $<0,v>=<v,0>=0$ where $<\_,\_>$ is a inner product on a vector space $V$.
8. Let $\{v_1,v_2\}$ are two vectors. Prove that $\{v_1,v_2-\frac{<v_1,v_2>}{||v_1||^2}v_1\}$ is orthogal set, [Note: $\frac{<v_1,v_2>}{||v_1||^2}v_1$ is called projection of $v_2$ onto $v_1$ and is denoted by $\operatorname{Proj}_{v_1}(v_2)=\frac{<v_1,v_2>}{||v_1||^2}v_1$]. If $\{v_1,v_2\}$ be linearly dependent then prove that $v_2-\frac{<v_1,v_2>}{||v_1||^2}v_1=0$ and converse is also easy.
9. **General version of question 8.** Prove that given any set of vectors $\{v_1,v_2,\cdots,v_n\}$ we have the orthogonal set of vectors $\{u_1,u_2,\cdots,u_n\}$ where 
$$u_1=v_1$$ and
$$u_k=v_k-\sum_{i=1}^{n-1} \frac{<v_k,u_i>}{||u_i||^2}u_i \quad \forall k\geq 2$$ [Hint: Prove this by induction. n=1 case is the question 8]

10.  Now, one you get the set of vectors in question 9 use question 8 and question 6 you get: Given a set of linearly independent set of vectors we have a orthonormal set of vectors. [**Important:** Can you tell what happens if you take linearly dependent set of vectors instead of linearly independent?]