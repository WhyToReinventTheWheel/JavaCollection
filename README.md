# Comparable

    class Movie implements Comparable<Movie>
    {
        private String name;
        private int year;

        // Used to sort movies by year
        public int compareTo(Movie m)
        {
            return this.year - m.year;
        }
    }
