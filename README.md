# BC-BNP

Bayesian non-parametric clustering.. of stuff

https://guides.github.com/features/mastering-markdown/



Running a notebook on the sirius cluster
```tcsh
conda activate py3
cd /gsfs0/data/aglinsai/BC-BNP/NoteBooks
set name='pyMC3-VI-Simulated-advi'


set dt=`date '+%d:%m:%Y:%H:%M:%S'`
echo 'Running Script' $name.ipynb
echo 'Starting'
echo 'Time now is '$dt

jupyter nbconvert --execute $name.ipynb --ExecutePreprocessor.timeout=-1 --to notebook --output $name'_'$dt.ipynb

echo 'Finished'
echo 'Time now is '$dt
```
