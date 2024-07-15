# Spotify Genre Enrichment

This project provides a Python script to enhance your Spotify streaming history or artist data by automatically retrieving and adding the primary genre associated with each artist.

## Features

*   **Automated Genre Retrieval:** Leverages the Spotify Web API to fetch artist genres.
*   **Data Enrichment:** Appends a "Genres" column to your existing Spotify dataset.
*   **Customizable:**  Easily adapt the script to work with your specific data format (CSV or Excel).
*   **Error Handling & Rate Limiting:**  Includes mechanisms to ensure robust and efficient API interactions.

## Getting Started

1.  **Prerequisites:**
    *   Python 3.x installed
    *   A Spotify Developer account with API credentials
    *   Your Spotify data file (in CSV or Excel format)

2.  **Installation:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Configuration:**

    *   Replace the placeholders `your_client_id` and `your_client_secret` in `get_artist_genres.py` with your actual Spotify API credentials.
    *   Update the file path in the script to point to your Spotify data file.

4.  **Usage:**

    ```bash
    python get_artist_genres.py
    ```

## Output

The script will create a new file named `artist_genres.csv` containing your original data with an additional "Genres" column.

## Disclaimer

This project is for educational purposes and personal use only. Be mindful of Spotify's API usage policies.

## License

This project is licensed under the MIT License.
