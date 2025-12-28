# Digital_Signal_Processing

Repository overview

This repository contains student assignments and supporting data for Digital Signal Processing (DSP) coursework. It includes two assignment directories that demonstrate practical work with the DFT and the 2D-DCT for image compression.

Folders

- `Harmonic_Detection_and_Interpolation/` — Live script, report, and resources for an assignment on DFT applications: detecting harmonic/sinusoidal signals in noise and interpolating sequences using the DFT. Key files:
  - `2_Harmonic_Detection_and_Interpolation.mlx` (MATLAB Live Script)
  - `2_Harmonic_Detection_and_Interpolation.pdf` (report)
  - `2_Harmonic_Detection_and_Interpolation.zip` (supporting data, may be empty)
  - `README.md` (assignment introduction and guidelines)

- `2D_DCT_Image_Compression_A2/` — Data and materials for a 2D-DCT image compression assignment. Key files:
  - `Assignment2_EN3551_ProblemStatement.pdf` (assignment brief)
  - `Assignment2_Submission_210321X.pdf` (student submission)
  - `Assignment2_Images_Allocation.xlsx` (image allocation / metadata)
  - `Assignment2_parrots.mat`, `Assignment2_barbara.mat`, `Assignment2_house.mat` (MAT-files with image data)
  - `README.md` (assignment introduction and guidelines)

How to use

- To view or run the Live Script, open the `.mlx` file in MATLAB (Live Editor). You can export it to a `.m` script if needed.
- PDF files contain problem statements and reports — open with any PDF viewer.
- `.mat` files can be loaded in MATLAB using `load('filename.mat')` to access variables for analysis and visualization.
- If a `.zip` contains supporting data, unzip it before use.

Notes about repository changes

I renamed and reorganized several files and directories to improve clarity (file prefixes removed/standardized, assignment folders renamed). Some renames were staged in git; other files were untracked before renaming. Run `git status` to review pending changes before committing.

If you want, I can:
- Stage and commit all changes with a single commit message.
- Revert or adjust any filenames or folder names.

Contact / Next steps

Tell me if you want me to commit the current changes, add a license, or generate example run commands for the MATLAB scripts.
# Digital_Signal_Processing