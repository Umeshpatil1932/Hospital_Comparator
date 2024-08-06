 Hospital Comparator

  Hospital Comparator is a Spring Boot application designed to help users compare hospitals based on Name, Amount, location, and specialties.
  
 Features

- Hospital Listings: Comprehensive list of hospitals.
- Comparison Tool: Compare hospitals by ratings, services, location, and specialties.
- Search Functionality: Search hospitals by name, location, or specialty.
- User Reviews: Read and write reviews for hospitals.
- Map Integration: View hospital locations on a map.

 Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Thymeleaf
- Bootstrap
- Google Maps API

 Setup Instructions

 Prerequisites

- Java 8 or higher
- Maven

 Steps

1. Clone the Repository:
 
   git clone https://github.com/Umeshpatil1932/Hospital_Comparator.git
   cd HospitalComparator
   

2. Configure Database:
   - Uses H2 database by default. For production, configure in `src/main/resources/application.properties`:
     properties
     spring.datasource.url=jdbc:mysql://localhost:3306/hospital_comparator
     spring.datasource.username=your_db_username
     spring.datasource.password=your_db_password
     

3. Build and Run:

   mvn clean install
   mvn spring-boot:run
   

4. Access the Application:
   - Navigate to `http://localhost:8080` in your web browser.

 Contribution Guidelines

- Fork the repository and create a branch for your changes.
- Add tests if applicable and ensure all tests pass.
- Submit a pull request with a clear description of your changes.


 Contact

For issues or questions, please open an issue or contact the maintainer at patilumesh1932@gmail.com.

Hospital Comparator helps users make informed decisions about healthcare by providing detailed hospital comparisons.
