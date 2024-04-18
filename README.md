<a name="readme-top"></a>

<!-- ABOUT THE PROJECT -->
## About The Project

We are downstream from NetSuite changes, and need to add new columns to tables on the fly.
The goal is to minimize having to do complete table reloads in dagster.
I.e. only pull the internal id and new column, join to target table, then add the column to Dagster for the nightly refresh.

<!-- GETTING STARTED -->
## Getting Started

### Installation

1. Clone the repo
   ```sh
   git clone 
   ```
2. Create venv.
   ```sh
   python -m venv .venv
   ```
3. Initialize venv.
   ```sh
   .\.venv\Scripts\activate
   ```
4. Install requirements.
   ```sh
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>