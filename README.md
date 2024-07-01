    <h1>Movie Recommendation System</h1>

    <h2>Overview</h2>
    <p>This project implements a movie recommendation system using the MovieLens 25M dataset. The system allows users to search for movies by title and provides recommendations based on the preferences of users who liked similar movies.</p>

    <h2>Installation</h2>
    <ol>
        <li>Download the MovieLens 25M dataset from <a href="https://files.grouplens.org/datasets/movielens/ml-25m.zip">here</a> and extract the <code>movies.csv</code> and <code>ratings.csv</code> files.</li>
        <li>Install the necessary Python libraries:
            <pre><code>pip install pandas scikit-learn numpy ipywidgets</code></pre>
        </li>
    </ol>

    <h2>Usage</h2>

    <h3>Input</h3>
    <ul>
        <li><strong>Movie Titles</strong>: The dataset consists of movie titles that are cleaned by removing special characters to standardize them for the search function.</li>
        <li><strong>User Ratings</strong>: User ratings are used to identify similar users who liked the same movie, which helps in generating movie recommendations.</li>
    </ul>

    <h3>Interactive UI</h3>
    <p>The system features an interactive widget that allows users to type in a movie title and receive recommendations in real-time. As the user types, the system searches for movies with similar titles and displays the top recommendations based on the preferences of users who liked the same movie.</p>

    <h3>Output</h3>
    <ul>
        <li><strong>Search Results</strong>: When a movie title is entered, the system returns the top 5 movies with similar titles.</li>
        <li><strong>Recommendations</strong>: Based on the selected movie, the system provides the top 10 movie recommendations. These recommendations are based on the ratings of users who liked similar movies. The output includes the recommendation score, movie titles, and genres.</li>
    </ul>

    <h2>Author</h2>
    <p>Implemented by Shloka Kulkarni.</p>
