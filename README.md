trackplot 0.3.7

```py
trackplot \
  -e chr16:5716-5718 \
  -r Mus_musculus.GRCm38.101.sorted.gtf \
  --density density_list.tsv \
  -o Tbc1d23.pdf \
  --dpi 300 \
  --width 6 \
  --height 1 --show-junction-num -t 5 \
  --site-color red,blue,red,red \
  --sites 5717,5711,5713,57136,5710 \
  --intron-scale .005
```
