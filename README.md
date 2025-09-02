# MyHome Scraper

This project scrapes property listings from MyHome.ge, saves the data as CSV, and generates PDFs for each listing.

## Workflow
1. `scraping_my_home.ipynb` – Scrapes listings and saves CSV.
2. `save_property_pdfs.ipynb` – Saves PDFs for each listing.

## Folder Structure
- `notebooks/` – Jupyter notebooks.
- `data/` – Ready-to-use CSV files.
- `property_pdfs/` – Generated PDFs.

## Dependencies
Install requirements via:
```bash
pip install -r requirements.txt
```
|       ID | Title                               | Price     |   Price per m² | Currency   | Location                    | District   |   Floors |   Rooms |   Bedroom(s) |   Square meter | Post Date    | URL                                                                    |
|---------:|:------------------------------------|:----------|---------------:|:-----------|:----------------------------|:-----------|---------:|--------:|-------------:|---------------:|:-------------|:-----------------------------------------------------------------------|
| 21994936 | იყიდება 2 ოთახიანი ბინა ვარკეთილში  | 175,110   |           3184 | ₾          | ჯავახეთის ქ.                | ვარკეთილი  |        5 |       2 |            1 |           55   | 02 სექ 11:18 | https://www.myhome.ge/pr/21994936/iyideba-2-otaxiani-bina-varketilshi/ |
| 21623262 | იყიდება 5 ოთახიანი ბინა ვაკეში      | 1,050,660 |           6486 | ₾          | ავალიშვილი ზ. ქ. 12         | ვაკე       |        7 |       5 |            3 |          162   | 02 სექ 11:00 | https://www.myhome.ge/pr/21623262/iyideba-5-otaxiani-bina-vakeshi/     |
| 21876517 | იყიდება 2 ოთახიანი ბინა საბურთალოზე | 228,990   |           4771 | ₾          | პოლიტკოვსკაია ა. ქ. (ჯიქია) | საბურთალო  |       10 |       2 |            1 |           48   | 02 სექ 11:00 | https://www.myhome.ge/pr/21876517/iyideba-2-otaxiani-bina-saburtaloze/ |
| 22161217 | იყიდება 3 ოთახიანი ბინა თბილისში    | 257,277   |           3066 | ₾          | ნადიკვარის დასახლების ქ.    | თბილისი    |        2 |       3 |            2 |           83.9 | 02 სექ 11:00 | https://www.myhome.ge/pr/22161217/iyideba-3-otaxiani-bina-tbilisshi/   |
| 22088448 | იყიდება 2 ოთახიანი ბინა საბურთალოზე | 363,690   |           6271 | ₾          | უნივერსიტეტის ქ. 20ა        | საბურთალო  |        2 |       2 |            1 |           58   | 02 სექ 10:56 | https://www.myhome.ge/pr/22088448/iyideba-2-otaxiani-bina-saburtaloze/ |
