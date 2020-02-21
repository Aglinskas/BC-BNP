# BC-BNP

Bayesian non-parametric clustering.. of stuff

https://guides.github.com/features/mastering-markdown/

cd /Users/aidasaglinskas/Desktop/BC-BNP/NoteBooks/

```bash
name='test'
dt=`date '+%d:%m:%Y:%H:%M:%S'`

echo 'Running Script' $name.ipynb
echo 'Starting'
echo 'Time now is '$dt

jupyter nbconvert --execute $name.ipynb --to notebook --output $name'_'$dt.ipynb

echo 'Finished'
echo 'Time now is '$dt
```
