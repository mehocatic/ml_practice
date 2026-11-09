# ml_practice

Vježba iz predmeta Mašinsko učenje (FIT, Univerzitet "Džemal Bijedić" u Mostaru).

## Tema

Predviđanje proizvodnje električne energije vjetroturbina (regresija). Meta je aktivna snaga turbine (`Patv`, kW), a predviđanje se radi sat unaprijed.

## Podaci

Skup podataka SDWPF (Spatial Dynamic Wind Power Forecasting), SCADA zapisi vjetroelektrane sa 134 turbine, 2020. do 2021.

- Izvor: https://doi.org/10.6084/m9.figshare.24798654
- Rad: Zhou et al., *SDWPF: A Dataset for Spatial Dynamic Wind Power Forecasting over a Large Turbine Array*, Scientific Data, 2024.

Podaci nisu u repozitoriju zbog veličine. Skini ih sa Figshare i stavi u folder `SDWPF_dataset/` (podfolder `sdwpf_full/`).

## Sadržaj

- `projekat.ipynb`: pregled podataka, kvalitet podataka, agregacija na satni nivo i hronološka podjela na razvojni i testni skup.

## Pokretanje

```
python -m pip install pandas numpy matplotlib seaborn scikit-learn pyarrow ipykernel
```

Zatim otvori `projekat.ipynb` u VS Code ili Jupyteru.
