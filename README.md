# Ancestry Grid for Carnegie Classification of Institutions of Higher Education

![image](https://github.com/user-attachments/assets/99f6f4d9-b9e6-43ce-a79c-bd36a8864034)
![image](https://github.com/user-attachments/assets/452d1b59-5d5e-424c-9e5f-bd5c9c0aa6bc)

A concise, interactive tool for exploring the historical lineage of U.S. higher education institutions using Carnegie Classification data from 1973–2021.

## Features

- **Dropdown Selection:** Choose institutions from an alphabetical, searchable dropdown.
- **Historical Names:** View current, past, and future names for each institution.
- **Timeline Visualization:** See institutional changes, mergers, absorptions, and degree status by year.
- **Efficient Loading:** Data partitioned into 10 institute name chunks (~60,000 rows) for fast, responsive UI.
- **Status Highlighting:** Degree-granting classification is clearly marked for each year.
- **Lineage Mapping:** Trace mergers, absorptions, and successor institutions with year-specific details.

## Data Structure

Each partition contains:
- Institution names (current and historical)
- Carnegie classification by year
- Merger/absorption events and years
- Successor/predecessor links
- Degree-granting status

## Usage

1. **Select** an institution from the dropdown or search box.
2. **View** its timeline: name changes, classification shifts, and merger history.
3. **Highlight** degree status and see transitions over the years.
4. **Explore** related institutions via lineage links.

## Classification Categories

- Doctoral Universities (R1, R2, R3)
- Master’s Colleges & Universities
- Baccalaureate Colleges
- Associate’s Colleges
- Special Focus Institutions
- Tribal Colleges

## Performance

- **Partitioned loading** ensures only relevant data is fetched, improving speed.
- **Incremental rendering** displays results as data loads.

## Contributing

Contributions are welcome! Please keep data partitioned and document all institutional relationship changes.

## License

MIT License

---

*This tool helps you quickly trace the evolution of U.S. higher education institutions and their Carnegie Classifications over time.*
