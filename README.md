import java.time.LocalDateTime;
import java.time.format.DateTimeFormatter;

public class DisplayInfo {
    public static void main(String[] args) {
        System.out.println("Full Name: Marcus Cedric A. Lamsen");
        LocalDateTime now = LocalDateTime.now();
        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss");
        System.out.println("Current Date and Time: " + now.format(formatter));
    }
}
