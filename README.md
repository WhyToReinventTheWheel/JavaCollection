# Sort


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


# Comparator

class AgeComparator implements Comparator<Student>{  
	public int compare(Student s1,Student s2){  
		if(s1.age==s2.age)  
			return 0;  
		else if(s1.age>s2.age)  
			return 1;  
		else  
			return -1;  
	}  
}
