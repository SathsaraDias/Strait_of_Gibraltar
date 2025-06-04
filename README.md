Here is a **professional and clear “How to Download .mat Files with Git LFS” section** you can add to your `README.md` for your GitHub repository.
This will guide users of **any OS** (Windows, macOS, Linux) step by step.

---

```markdown
# Strait_of_Gibraltar

This dataset provides 3D ocean current simulations of the Strait of Gibraltar, including zonal (U), meridional (V), and vertical velocity components (W) at grid coordinates (X,Y, Z), (X: longitude, Y: latitude, Z: depth, in m). The simulation was conducted using the MIT General Circulation Model. The data set consists of 144 hourly snapshots over six days. Modelled ocean features, which include tidal flows, ocean gyres, and internal gravity waves, were analyzed using Dynamic Mode Decomposition (DMD).

## How to Download the .mat Data File

**Large files in this repository are tracked using [Git Large File Storage (LFS)](https://git-lfs.com/).**  
If you see a small pointer file instead of the real `.mat` file, you need to install Git LFS to download the actual data.

### Step 1: Install Git LFS

- **Windows:**  
  Download and run the installer from [git-lfs.github.com](https://git-lfs.github.com/).  
  Then, open a terminal (e.g., Git Bash or Command Prompt) and run:  
```

git lfs install

```

- **macOS:**  
```

brew install git-lfs
git lfs install

```

- **Linux (Debian/Ubuntu):**  
```

sudo apt-get install git-lfs
git lfs install

````

For other distros, see [Git LFS installation instructions](https://github.com/git-lfs/git-lfs/wiki/Installation).

### Step 2: Clone the Repository and Download Large Files

In your terminal, run:
```bash
git clone https://github.com/your-username/Strait_of_Gibraltar.git
cd Strait_of_Gibraltar
git lfs pull
````

*(Replace the URL above with your actual repository URL if it is different.)*

This will download the **real** `.mat` file(s) instead of just the pointer files.

---

**If you have already cloned the repository but only see a small text file instead of the actual `.mat` file:**

1. Install Git LFS (as above).
2. Inside your repo folder, run:

   ```
   git lfs pull
   ```

---

For more help, see the [Git LFS Documentation](https://git-lfs.github.com/).

If you have any issues or questions, feel free to open an issue on this repository!

```

---

- This will make your repository much more user-friendly for people not familiar with Git LFS.
- Adjust the repo URL as needed.

Let me know if you want it shortened, or want a one-liner for “just download the .mat file” for non-GitHub-savvy users!
```
