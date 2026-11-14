# Ideas and New Concepts by Lecture

A concise map of **pedagogical ideas** (`@idea` tags) and **new concepts** (`@introduces`) for each lecture, in course order.

---

## Starts that build on the *previous* lecture’s end

These are places where the **first part of a lecture** is giving conceptual understanding (or a direct extension) for a concept or idea that was introduced **at or near the end** of the previous lecture—i.e. “going back to make it hit home” or “picking up where we left off.”

| Next lecture | First idea / opening | Previous lecture’s last intro / idea |
|--------------|----------------------|--------------------------------------|
| **Day 2** | `rref_free_bound_and_consistency` — "Intuitions about RRE form," systems with non-unique solutions, free vs bound variables. | Day 1 ends with `ill_conditioning` and `polynomial_interpolation_example`; Day 2 starts by going back to RREF (introduced earlier in Day 1) to build intuition before introducing free/bound and consistency. |
| **Day 3** | `diffusion_and_boundary_conditions` — “Last week, we talked about the **diffusion equation**…” | Day 2 ends with `reaction_diffusion_biology` (Turing patterns); Day 3 starts by building the diffusion foundation (equation, boundary conditions, discretization). |
| **Day 8** | `linear_independence_and_invertibility` — “Connects to solving systems … one way of stating that a matrix is invertible is if $\mathbf{c}=0$ is the only solution to $A\mathbf{c}=\mathbf{0}$.” | Day 7 ends with `determinants_and_invertibility` and introduces `determinant`. Day 8 opens by tying linear independence to invertibility (the theme from the end of Day 7). |
| **Day 9** | `column_space_geometry` — “Geometrical View of Column Space,” “Why column space matters,” “Seeing $\mathcal{C}(A)$ as a line or plane.” | Day 8 ends with `fundamental_subspaces` and introduces `column_space`, `row_space`, `null_space`; it explicitly says “Geometric picture (next lecture).” Day 9 delivers that geometric picture. |
| **Day 10** | `normal_equations_multiple_predictors` — “Extending the normal equations to multiple predictors.” | Day 9 ends with `least_squares_and_normal_equations` and introduces `normal_equations`. Day 10 starts by extending the normal equations (multiple predictors, matrix form). |
| **Day 12b** | `svd_from_diagonalization_intuition` — “Intuition about SVD,” “Thinking again about matrix diagonalization” then “The same logic, applied to a general matrix” (SVD). | Day 12a ends with `singular_values_and_svd_theorem` and introduces `singular_value_decomposition`. Day 12b starts by building intuition for SVD via diagonalization. |

---

## Day 1 — Intro to Linear Systems

**Ideas**

| Idea | Description |
|------|--------------|
| `linear_systems_what_and_why` | What linear systems are and why we care |
| `examples_of_linear_systems` | Railroad, traffic flow, polynomial interpolation |
| `from_equations_to_augmented_matrix` | From equations to matrix form and augmented matrix |
| `elementary_operations_and_rref` | Row operations and reduced row echelon form |
| `gauss_jordan_algorithm` | Gauss–Jordan elimination algorithm |
| `rounding_mining_and_goals` | Rounding in elimination, mining example, algorithm goals |
| `roundoff_and_partial_pivoting` | Roundoff errors and partial pivoting |
| `ill_conditioning` | Ill-conditioned systems and sensitivity |
| `polynomial_interpolation_example` | Polynomial interpolation as ill-conditioned example |

**New concepts:** linear_system, augmented_matrix, elementary_row_operations, reduced_row_echelon_form, gauss_jordan_elimination, pivoting, pivot, ill_conditioning

---

## Day 2 — More Systems of Linear Equations

**Ideas**

| Idea | Description |
|------|--------------|
| `rref_free_bound_and_consistency` | RREF, free vs bound variables, consistency |
| `pagerank_tutorial` | PageRank as matrix equation |
| `diffusion_discretization` | Discretizing continuous functions (diffusion) |
| `reaction_diffusion_biology` | Reaction–diffusion and Turing patterns |

**New concepts:** free_and_bound_variables, basic_column, consistent_system, rank, nullity, homogeneous_system

---

## Day 3 — Reaction–Diffusion & Matrix Arithmetic

**Ideas**

| Idea | Description |
|------|--------------|
| `diffusion_and_boundary_conditions` | Diffusion equation and boundary conditions |
| `reaction_diffusion_solving` | Solving and animating reaction–diffusion |
| `matrix_arithmetic_review` | Matrix addition, multiplication, linear combination |
| `transformations_scaling_rotation` | Scaling, shearing, rotation as transformations |

**New concepts:** linear_combination, linear_map

---

## testLightbox

**Ideas:** —  
**New concepts:** —

---

## Day 4 — Discrete Dynamical Systems & Graphs

**Ideas**

| Idea | Description |
|------|--------------|
| `dynamical_systems_and_markov` | Definitions, stability, Markov chains |
| `graphs_and_adjacency` | Graphs, digraphs, adjacency matrix |

**New concepts:** discrete_dynamical_system, transition_matrix, stationary_vector, distribution_vector, stochastic_matrix, markov_chain, graph, directed_graph, adjacency_matrix

---

## Day 5 — Difference Equations, Filters, Inverses, PageRank

**Ideas**

| Idea | Description |
|------|--------------|
| `difference_equations_intro` | Difference equations |
| `digital_filters_example` | Digital filters, low/high-pass |
| `inverse_matrices_and_algorithm` | Inverse definition, conditions, algorithm |
| `pagerank_as_markov` | PageRank as Markov chain |

**New concepts:** lowpass_filter, highpass_filter, inverse_matrix, elementary_matrix, superaugmented_matrix

---

## plots_for_lecture_3

**Ideas:** —  
**New concepts:** —

---

## Day 6 — MCMC, RBM, LU/PLU

**Ideas**

| Idea | Description |
|------|--------------|
| `mcmc_and_gibbs_sampling` | Idea of MCMC |
| `rbm_training_and_gibbs` | Restricted Boltzmann machine, training, Gibbs |
| `lu_factorization_saving_work` | LU factorization and solving triangular systems |
| `plu_factorization` | PLU with row swaps |

**New concepts:** lu_factorization, permutation_matrix

---

## Day 7 — Block Multiplication, Transpose, Determinants

**Ideas**

| Idea | Description |
|------|--------------|
| `block_multiplication` | Block matrices and multiplication |
| `transpose_and_symmetric` | Transpose, conjugate transpose, symmetric/Hermitian |
| `inner_and_outer_products` | Inner and outer products |
| `quadratic_forms` | Quadratic forms $\mathbf{x}^T A \mathbf{x}$ |
| `determinants_and_invertibility` | Determinants, laws, invertibility |

**New concepts:** block_multiplication, transpose, determinant

---

## Day 8 — Linear Independence, Vector Spaces, Fundamental Subspaces

**Ideas**

| Idea | Description |
|------|--------------|
| `linear_independence_and_invertibility` | Linear independence and connection to invertibility |
| `vector_spaces_and_basis` | Vector spaces, $\mathbb{R}^n$, axioms |
| `spanning_sets_and_standard_basis` | Spanning sets, basis, standard basis |
| `fundamental_subspaces` | Column space, row space, null space |
| `applications_markov_and_consistency` | Markov steady state, consistency, solution geometry |

**New concepts:** linear_independence, span, basis, subspace, column_space, row_space, null_space

---

## Day 9 — Column Space Geometry, Planes, Least Squares

**Ideas**

| Idea | Description |
|------|--------------|
| `column_space_geometry` | Column space as line/plane, rank |
| `planes_and_projections` | Planes, hyperplanes, projection onto plane |
| `least_squares_and_normal_equations` | Least squares, project $\mathbf{b}$ onto $\mathcal{C}(A)$, normal equations |

**New concepts:** left_null_space, projection, least_squares, normal_equations

---

## Day 10 — More Least Squares, Orthogonality, QR, Haar

**Ideas**

| Idea | Description |
|------|--------------|
| `normal_equations_multiple_predictors` | Normal equations for multiple predictors |
| `orthogonal_and_orthonormal_sets` | Orthogonal/orthonormal sets, orthogonal matrices |
| `gram_schmidt_and_orthonormal_basis` | Gram–Schmidt and orthonormal bases |
| `qr_factorization_and_least_squares` | QR factorization and least squares |
| `haar_wavelet_and_compression` | Haar wavelet and image compression |

**New concepts:** orthogonal_set, orthonormal_set, orthogonal_matrix, unitary_matrix, gram_schmidt, qr_factorization

---

## Day 11a — Eigenvalues and Eigenvectors

**Ideas**

| Idea | Description |
|------|--------------|
| `eigenvalues_eigenspaces_algorithm` | Eigenvalues, eigenspaces, characteristic equation |
| `diagonalization_and_similarity` | Diagonalization, similar matrices |
| `spectral_radius_and_dynamics` | Spectral radius, dominant eigenvalue, dynamics |

**New concepts:** eigenvalue, eigenvector, eigenspace, diagonalization, spectral_radius, dominant_eigenvalue

---

## Day 11b

**Ideas:** —  
**New concepts:** —

---

## Day 12a — Symmetric Matrices, SVD

**Ideas**

| Idea | Description |
|------|--------------|
| `symmetric_matrices_spectral_theorem` | Positive definite, spectral theorem for symmetric matrices |
| `diagonalizing_quadratic_forms` | Quadratic forms and orthogonal diagonalization |
| `coupled_springs_diagonalization` | Coupled springs, diagonalization |
| `singular_values_and_svd_theorem` | Singular values, SVD theorem, geometry |

**New concepts:** singular_value, right_singular_vector, left_singular_vector, singular_value_decomposition

---

## Day 12b — SVD Intuition, Pseudoinverse, Data

**Ideas**

| Idea | Description |
|------|--------------|
| `svd_from_diagonalization_intuition` | SVD intuition from diagonalization |
| `pseudoinverse_and_least_squares` | Moore–Penrose pseudoinverse |
| `data_matrices_and_covariance` | Matrices as data, covariance, U/V interpretation |

**New concepts:** —

---

## SVD Interlude — Geometric Buildup to SVD

**Ideas**

| Idea | Description |
|------|--------------|
| `input_output_orthogonal_directions` | Input/output spaces, orthogonal directions that stay orthogonal |
| `from_rank_to_svd_matrix_form` | From rank to SVD, matrix form, geometric interpretation |

**New concepts:** —

---

## Day 14 — SVD on Data, Images, PCA

**Ideas**

| Idea | Description |
|------|--------------|
| `svd_on_tabular_data` | SVD on matrices of data, U and V |
| `svd_on_images_and_pca` | SVD on images, PCA as truncated SVD |
| `pca_high_dimensional_data` | PCA on high-dimensional data (e.g. faces) |

**New concepts:** principal_component

---

## test

**Ideas**

| Idea | Description |
|------|--------------|
| `test_slide` | Test slide |

**New concepts:** —

---

## Day 15 — High-Dimensional Data, PCA, Interpretation

**Ideas**

| Idea | Description |
|------|--------------|
| `high_dimensional_data_and_projection` | Variance, projection onto fewer dimensions |
| `first_principal_component_definition` | First PC: eigenvector for largest eigenvalue, first right singular vector |
| `shopping_baskets_exploration` | Shopping baskets, exploration before PCA |
| `interpreting_principal_components` | Loadings vs scores, interpreting PCs |

**New concepts:** —

---

## Day 18a — Discrete Filters, DTFT, Gain

**Ideas**

| Idea | Description |
|------|--------------|
| `discrete_filters_dtft_and_gain` | Discrete-time filters, DTFT, gain, phase, low/high-pass |

**New concepts:** discrete_filter, finite_impulse_response_filter, discrete_time_fourier_transform, filter_gain, phase_rotation

---

## Day 18 Review

**Ideas**

| Idea | Description |
|------|--------------|
| `review_linear_systems` | Chapter 1: linear systems |
| `review_matrices` | Chapter 2: matrices |
| `review_vector_spaces` | Chapter 3: vector spaces |
| `review_orthogonality` | Chapter 4: orthogonality |
| `review_eigenvalues_svd_pca` | Chapter 5: eigenvalues, SVD, PCA |
| `review_fourier` | Chapter 6: Fourier transform |

**New concepts:** —

---

## ChNone — Fourier Series and DFT

**Ideas**

| Idea | Description |
|------|--------------|
| `fourier_series_and_orthogonality` | Fourier series, orthogonality, coefficients |
| `discrete_fourier_series_and_dft` | Discrete Fourier series, DFT matrix |
| `dft_filtering_and_convolution` | Filtering, convolution theorem |

**New concepts:** —

---

*Generated from `course_state.yaml` and `@idea` / `@introduces` tags in lecture `.qmd` files.*
