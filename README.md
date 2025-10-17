# ai-code-executor

The ai-code-executor tool provides a secure, stateful Python REPL environment with pre-installed libraries tailored for STEM, data analysis, and creative tasks. These libraries are grouped by category below, along with brief descriptions of their primary uses. Note that the environment runs on Python 3.12.3, and you cannot install additional packages—everything must be imported directly from these.

## Basic Utilities
- **tqdm**: Progress bars for loops and tasks, ideal for tracking long-running computations.
- **ecdsa**: Elliptic Curve Digital Signature Algorithm for cryptographic operations.

## Data Processing
- **numpy**: Fundamental package for numerical computing with arrays and mathematical functions.
- **scipy**: Scientific computing tools, including optimization, integration, and signal processing.
- **pandas**: Data manipulation and analysis, especially for tabular data (e.g., DataFrames).
- **matplotlib**: Plotting and visualization library for creating static, animated, and interactive graphs.
- **openpyxl**: Reading and writing Excel files (.xlsx) with support for formatting and charts.

## Mathematics
- **sympy**: Symbolic mathematics for algebra, calculus, and equation solving.
- **mpmath**: Arbitrary-precision floating-point arithmetic for high-precision calculations.
- **statsmodels**: Statistical modeling, including regression, time-series analysis, and hypothesis testing.
- **PuLP**: Linear programming and optimization problems.

## Physics
- **astropy**: Astronomy and astrophysics tools, such as coordinate transformations and unit handling.
- **qutip**: Quantum optics and dynamics simulations for quantum information science.
- **control**: Control systems library for modeling and analyzing dynamic systems.

## Biology
- **biopython**: Bioinformatics toolkit for sequence analysis, alignments, and biological data structures.
- **pubchempy**: Interface to PubChem for accessing chemical and biological compound data.
- **dendropy**: Phylogenetic tree manipulation and analysis for evolutionary biology.

## Chemistry
- **rdkit**: Cheminformatics for molecule manipulation, descriptors, and chemical informatics.
- **pyscf**: Quantum chemistry calculations, including Hartree-Fock and density functional theory.

## Finance
- **polygon**: API client for real-time and historical financial market data (internet access proxied).

## Cryptocurrency
- **coingecko**: API client for cryptocurrency prices, market data, and exchange info (internet access proxied).

## Game Development
- **pygame**: 2D game development with graphics, sound, and input handling.
- **chess**: Chess game logic, board representation, and move validation.

## Multimedia
- **mido**: MIDI file handling and real-time MIDI message processing.
- **midiutil**: Creating and editing MIDI files programmatically.

## Machine Learning & Graphs
- **networkx**: Network analysis and graph algorithms (e.g., social networks, biology graphs).
- **torch**: PyTorch for deep learning, tensor computations, and neural networks.

## Others
- **snappy**: Compression library for fast data compression and decompression.

These libraries enable a wide range of workflows, from data visualization and scientific simulations to financial modeling and game prototyping. For example, you could use pandas with matplotlib for quick data plots or torch for building simple ML models—all while preserving session state for iterative coding.
