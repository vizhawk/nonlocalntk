The Neural Tangent Kernel (NTK) framework has provided deep
insights into the training dynamics of neural networks under gradient

flow. However, it relies on the assumption that the network is differen-
tiable with respect to its parameters, an assumption that breaks down

when considering non-smooth target functions or parameterized mod-
els exhibiting non-differentiable behavior. In this work, we propose

a Nonlocal Neural Tangent Kernel (NNTK) that replaces the local

gradient with a nonlocal interaction-based approximation in parame-
ter space. Nonlocal gradients are known to exist for a wider class of

functions than the standard gradient. This allows NTK theory to be
extended to nonsmooth functions, stochastic estimators, and broader
families of models. We explore both fixed-kernel and attention-based

formulations of this nonlocal operator. We illustrate the new formula-
tion with numerical studies.
