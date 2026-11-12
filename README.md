# Outer Multiset Dimension of Three-Dimensional Grids

**A Universal Lower Bound and an Exact Two-Parameter Classification**

Ryutaro Yonezu, Independent Researcher  
Research No.59 · Preprint v1.0 · 8 November 2026

For all integers a, b, c ≥ 2, the outer multiset dimension of `P_a □ P_b □ P_c` is at least 4. For 2 ≤ m ≤ n, the outer multiset dimension of `P_2 □ P_m □ P_n` is 4 if n ≥ 6 or (m, n) is (2, 5) or (4, 5). Its value is 5 in the other eight small cases. The proof combines analytic arguments, exhaustive finite checks, and exact-rational certificates.

This result is a candidate partial response to Farhan et al., Problem 10. No.58 already established the m = 3, n ≥ 6 subfamily. Its B(t) landmark family and even-N interior collision witnesses overlap the earlier F3 (x-type) construction in No.59, represented in Type II-a after a grid symmetry. The shared construction is credited to No.58. [No.58 v1.0 GitHub Release](https://github.com/yonezaemon1-hub/no58-outer-multiset-dimension-3d-grid/releases/tag/v1.0) · [No.58 version DOI](https://doi.org/10.5281/zenodo.24024946)

## Review and rights

- Independent AI audit PASS within the author-reported Rev2 differential scope. It covered mathematical invariance, the 23-file source manifest, frozen v0.5/v0.6 reproduction, and the SymPy certificate for 22 branches (264 coordinate bounds, 154 distinctness and exteriority conditions, and 26 absolute-value sign checks).
- Author-reported Windows PowerShell 5.1 reproduction PASS for the frozen v0.5 finite computation.
- **REFERENCES PARTIAL. NOVELTY INCONCLUSIVE. Not human peer-reviewed. All rights reserved.**

## Files

- [Preprint PDF](No59_v1.0_PREPRINT_20261108.pdf)
- [LaTeX source](No59_v1.0_PREPRINT_20261108.tex)
- [Reproducibility ZIP](No59_v1.0_REPRODUCIBILITY_20261108.zip)
- [SHA256 checksums](SHA256SUMS.txt)

The reproducibility archive also contains the manuscript, the frozen computational files selected for public reproduction, the 22-branch certificate, and a release changelog. The manifest inside the archive applies to its own contents. The SHA256 file next to the download applies to the PDF, TeX and ZIP.

## Reproduce from the extracted ZIP

On Linux, use Bash, a C++17 compiler, Python 3.10 or later, and GNU coreutils. The SymPy certificate was replayed with SymPy 1.14.0.

~~~sh
sha256sum -c SHA256SUMS.txt
bash frozen/v0.5/REPRODUCE.sh
python -B -I frozen/v0.6/REPRODUCE.py
python -B -I supplement/verify_exact_22_bounds.py
~~~

The v0.5 runner compares both C++17 outputs and the independent BFS output with the bundled evidence. The v0.6 runner checks 4,096 local sign configurations, 22 affine identities, 22,464 finite integer checks, and six moment polynomial identities. The additional SymPy verifier checks the 22 branch domains using exact rational arithmetic. Its expected output and branch table are in the supplement. On Windows PowerShell 5.1, run the selected v0.5 runner from the extracted directory with Python and g++ on PATH.

~~~powershell
powershell.exe -NoProfile -File .\frozen\v0.5\run_windows.ps1
~~~

The public bundle uses new manifests for its selected files. The v0.5 and v0.6 verifier and runner bytes match the corresponding files in the original frozen archives.

## Cite

Ryutaro Yonezu (2026). *Outer Multiset Dimension of Three-Dimensional Grids: A Universal Lower Bound and an Exact Two-Parameter Classification*. Research No.59, preprint v1.0.

[Zenodo record](https://zenodo.org/records/24045061) · [Version DOI 10.5281/zenodo.24045061](https://doi.org/10.5281/zenodo.24045061)

## Author correspondence (metadata update, 2026-11-12)

**Ryutaro Yonezu — Independent Researcher**  
Research correspondence: **yonezaemon1+research@gmail.com**

This contact-information addition does not revise any mathematical claims, frozen verification files, published preprint PDF, release assets, DOI, or existing SHA256 checksums.
