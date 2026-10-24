---
format: html
---

# Table of Contents: Ideas, Uses, and Introduces

By lecture (file order). For each **idea** we list **uses** (concepts/groups referenced) and **introduces** (concepts first introduced in that idea block).

---

## Day 1 — Intro to Linear Systems (`day_1.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `linear_systems_what_and_why` | linear_system, linear_systems_core | linear_system |
| `examples_of_linear_systems` | linear_system, linear_systems_core | — |
| `from_equations_to_augmented_matrix` | augmented_matrix, elimination_and_rref, linear_system, linear_systems_core | augmented_matrix |
| `elementary_operations_and_rref` | augmented_matrix, elimination_and_rref, elementary_row_operations, linear_system, reduced_row_echelon_form | elementary_row_operations, reduced_row_echelon_form |
| `gauss_jordan_algorithm` | augmented_matrix, elimination_and_rref, elementary_row_operations, gauss_jordan_elimination, pivot, pivoting, reduced_row_echelon_form | gauss_jordan_elimination, pivoting, pivot |
| `rounding_mining_and_goals` | augmented_matrix, elimination_and_rref, gauss_jordan_elimination, linear_system, reduced_row_echelon_form | — |
| `roundoff_and_partial_pivoting` | elimination_and_rref, gauss_jordan_elimination, linear_system, pivot, pivoting | — |
| `ill_conditioning` | ill_conditioning, linear_system, linear_systems_core | ill_conditioning |
| `polynomial_interpolation_example` | elimination_and_rref, gauss_jordan_elimination, ill_conditioning, linear_system, linear_systems_core, pivoting | — |

---

## Day 2 — More Systems of Linear Equations (`day_2.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `rref_free_bound_and_consistency` | augmented_matrix, basic_column, consistent_system, elimination_and_rref, free_and_bound_variables, homogeneous_system, linear_system, linear_systems_core, nullity, rank, rank_and_nullity, reduced_row_echelon_form | free_and_bound_variables, basic_column, consistent_system, rank, nullity, homogeneous_system |
| `pagerank_tutorial` | distribution_vector, dynamical_and_markov, markov_chain, stationary_vector, stochastic_matrix, transition_matrix | — |
| `diffusion_discretization` | linear_system | — |
| `reaction_diffusion_biology` | linear_system | — |

---

## Day 3 — Ch2 Lecture 1 (`day_3.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `diffusion_and_boundary_conditions` | linear_system | — |
| `reaction_diffusion_solving` | linear_system | — |
| `matrix_arithmetic_review` | linear_combination, linear_system, linear_map, matrix_arithmetic | linear_combination, linear_map |
| `transformations_scaling_rotation` | linear_map, matrix_arithmetic | — |

---

## Day 4 — Ch2 Lecture 2 (`day_4.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `dynamical_systems_and_markov` | discrete_dynamical_system, distribution_vector, dynamical_and_markov, markov_chain, stationary_vector, stochastic_matrix, transition_matrix | discrete_dynamical_system, transition_matrix, stationary_vector, distribution_vector, stochastic_matrix, markov_chain |
| `graphs_and_adjacency` | adjacency_matrix, directed_graph, graph, graphs | graph, directed_graph, adjacency_matrix |

---

## Day 5 — Ch2 Lecture 3 (`day_5.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `difference_equations_intro` | linear_system | — |
| `digital_filters_example` | discrete_filters, highpass_filter, lowpass_filter | lowpass_filter, highpass_filter |
| `inverse_matrices_and_algorithm` | elementary_matrix, inverse_matrix, inverses_and_factorization, superaugmented_matrix | inverse_matrix, elementary_matrix, superaugmented_matrix |
| `pagerank_as_markov` | dynamical_and_markov, markov_chain, stationary_vector, transition_matrix | — |

---

## Day 6 — Ch2 Lecture 4 (`day_6.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `mcmc_and_gibbs_sampling` | markov_chain | — |
| `rbm_training_and_gibbs` | markov_chain | — |
| `lu_factorization_saving_work` | inverses_and_factorization, linear_system, lu_factorization | lu_factorization |
| `plu_factorization` | inverses_and_factorization, lu_factorization, permutation_matrix, superaugmented_matrix | permutation_matrix |

---

## Day 7 — Ch2 Lecture 5 (`day_7.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `block_multiplication` | block_multiplication, matrix_arithmetic | block_multiplication |
| `transpose_and_symmetric` | matrix_arithmetic, transpose | transpose |
| `inner_and_outer_products` | matrix_arithmetic, transpose | — |
| `quadratic_forms` | transpose | — |
| `determinants_and_invertibility` | determinant, inverse_matrix, inverses_and_factorization | determinant |

---

## Day 8 — Ch3 Lecture 1 (`day_8.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `linear_independence_and_invertibility` | independence_and_span, inverse_matrix, linear_independence | linear_independence |
| `vector_spaces_and_basis` | basis, fundamental_subspaces, independence_and_span, span, subspace | — |
| `spanning_sets_and_standard_basis` | basis, independence_and_span, span | span, basis |
| `fundamental_subspaces` | column_space, fundamental_subspaces, left_null_space, null_space, row_space, subspace | subspace, column_space, row_space, null_space |
| `applications_markov_and_consistency` | consistent_system, dynamical_and_markov, markov_chain, stationary_vector, transition_matrix | — |

---

## Day 9 — Ch4 Lecture 1 (`day_9.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `column_space_geometry` | column_space, fundamental_subspaces | — |
| `planes_and_projections` | column_space, least_squares_and_projection, projection | left_null_space, projection |
| `least_squares_and_normal_equations` | least_squares, least_squares_and_projection, normal_equations, projection | least_squares, normal_equations |

---

## Day 10 — Ch4 Lecture 2 (`day_10.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `normal_equations_multiple_predictors` | least_squares, least_squares_and_projection, normal_equations, projection | — |
| `orthogonal_and_orthonormal_sets` | orthogonal_and_qr, orthogonal_set, orthonormal_set | orthogonal_set, orthonormal_set, orthogonal_matrix, unitary_matrix |
| `gram_schmidt_and_orthonormal_basis` | gram_schmidt, orthogonal_and_qr, orthonormal_set | gram_schmidt |
| `qr_factorization_and_least_squares` | least_squares, orthogonal_and_qr, qr_factorization | qr_factorization |
| `haar_wavelet_and_compression` | orthonormal_set, qr_factorization | — |

---

## Day 11a — Ch5 Lecture 1 (`day_11a.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `eigenvalues_eigenspaces_algorithm` | diagonalization, eigenvalue, eigenvector, eigenspace, eigenvalue_eigenvector | eigenvalue, eigenvector, eigenspace |
| `diagonalization_and_similarity` | diagonalization, eigenvalue, eigenvector, eigenvalue_eigenvector | diagonalization |
| `spectral_radius_and_dynamics` | dominant_eigenvalue, eigenvalue, eigenvalue_eigenvector, spectral_radius | spectral_radius, dominant_eigenvalue |

---

## Day 12a — Ch5 Lecture 2 (`day_12a.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `symmetric_matrices_spectral_theorem` | diagonalization, eigenvalue, eigenvector, eigenvalue_eigenvector, orthogonal_set | — |
| `diagonalizing_quadratic_forms` | diagonalization, eigenvalue, eigenvector, eigenvalue_eigenvector | — |
| `coupled_springs_diagonalization` | diagonalization, eigenvalue, eigenvector, eigenvalue_eigenvector | — |
| `singular_values_and_svd_theorem` | eigenvalue, eigenvector, singular_value, singular_value_decomposition, svd, svd_core | singular_value, right_singular_vector, left_singular_vector, singular_value_decomposition |

---

## Day 12b — Ch5 Lecture 3 (`day_12b.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `svd_from_diagonalization_intuition` | diagonalization, eigenvalue, eigenvector, singular_value_decomposition, svd | — |
| `pseudoinverse_and_least_squares` | least_squares, least_squares_and_projection, singular_value_decomposition, svd | — |
| `data_matrices_and_covariance` | least_squares, singular_value_decomposition, svd | — |

---

## SVD Interlude (`svd_interlude.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `input_output_orthogonal_directions` | column_space, left_singular_vector, right_singular_vector, singular_value, singular_value_decomposition, svd_core | — |
| `from_rank_to_svd_matrix_form` | rank, singular_value_decomposition, svd, svd_core | — |

---

## Day 14 — Ch5 Lecture 4 (`day_14.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `svd_on_tabular_data` | left_singular_vector, right_singular_vector, singular_value, singular_value_decomposition, svd, svd_core | — |
| `svd_on_images_and_pca` | pca, principal_component, singular_value_decomposition, svd, svd_core | principal_component |
| `pca_high_dimensional_data` | pca, principal_component, singular_value_decomposition, svd | — |

---

## Day 15 — Ch5 Lecture 5 (`day_15.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `high_dimensional_data_and_projection` | projection | — |
| `first_principal_component_definition` | eigenvalue, eigenvector, pca, principal_component, right_singular_vector, singular_value | — |
| `shopping_baskets_exploration` | pca, principal_component | — |
| `interpreting_principal_components` | pca, principal_component | — |

---

## Day 18a — Ch6 Fourier (`day_18a.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `discrete_filters_dtft_and_gain` | discrete_filter, discrete_filters, discrete_time_fourier_transform, filter_gain, finite_impulse_response_filter, phase_rotation | discrete_filter, finite_impulse_response_filter, discrete_time_fourier_transform, filter_gain, phase_rotation |

---

## Day 18 — Review (`day_18_review.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `review_linear_systems` | elimination_and_rref, linear_system, linear_systems_core, reduced_row_echelon_form | — |
| `review_matrices` | linear_combination, linear_map, matrix_arithmetic | — |
| `review_vector_spaces` | basis, column_space, fundamental_subspaces, independence_and_span, linear_independence, null_space, span, subspace | — |
| `review_orthogonality` | least_squares, least_squares_and_projection, normal_equations, orthogonal_and_qr, projection, qr_factorization | — |
| `review_eigenvalues_svd_pca` | eigenvalue, eigenvector, eigenvalue_eigenvector, pca, principal_component, singular_value_decomposition, svd | — |
| `review_fourier` | discrete_filters, discrete_time_fourier_transform, filter_gain | — |

---

## ChNone — Fourier (standalone) (`ChNone.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `fourier_series_and_orthogonality` | orthogonal_set, orthonormal_set | — |
| `discrete_fourier_series_and_dft` | discrete_time_fourier_transform, discrete_filters | — |
| `dft_filtering_and_convolution` | discrete_filter, discrete_filters, filter_gain | — |

---

## Test (`test.qmd`)

| Idea | Uses | Introduces |
|------|------|------------|
| `test_slide` | linear_system | — |

---

*Generated from `@idea`, `@uses`, and `@introduces` tags in lecture `.qmd` files. Concept and group ids match `course_concepts.yaml`.*
