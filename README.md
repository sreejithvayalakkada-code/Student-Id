# Student-Id
Here is the link to the flowchart:
https://app.diagrams.net/#G1i8HGwaad27gCdRBKQPEBIbQgZpeefMij#%7B%22pageId%22%3A%22kwSHGt6Fc0E7g4eH6lI1%22%7D
Here is the link to the code: 
https://onecompiler.com/java/43xtudtqb
Here is the link to my video:
https://screenpal.com/content/video/cTQOfxnD0Mz?top-banner=online-recorder-details
Here is the actual code:
public class Student {
    private String name;
    private int age;
    private String id;

    // Constructor
    public Student(String name, int age, String id) {
        this.name = name;
        this.age = age;
        this.id = id;
    }

    // Getters (optional setters if you need mutability)
    public String getName() { return name; }
    public int getAge() { return age; }
    public String getId() { return id; }

    @Override
    public String toString() {
        return "Student{name='" + name + "', age=" + age + ", id='" + id + "'}";
    }

    // Example usage
    public static void main(String[] args) {
        Student s = new Student("Smith", 20, "9999");
        System.out.println(s); // uses toString()
        // Or print fields individually:
        System.out.println("Name: " + s.getName());
        System.out.println("Age: " + s.getAge());
        System.out.println("ID: " + s.getId());
    }
}
