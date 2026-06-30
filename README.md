# DVC Data Download

After cloning the repository, install DVC with Google Drive support using `python -m pip install "dvc[gdrive]"`, then run `dvc pull`.

This command will download `data/train_data.csv`, `data/test_data.csv`, and `data/sample_submission.csv`, while GitHub stores only the lightweight `.dvc` tracking files.

## Example

```powershell
cd C:\Users\asus\Desktop
git clone https://github.com/Marwan-Ahmad/ForDVC.git ForDVC_test_pull
cd ForDVC_test_pull
python -m pip install "dvc[gdrive]"
dvc pull
dir data