Today topic VERY IMPORTANT:

⭐ IOC Container
⭐ Beans
⭐ Dependency Injection
⭐ @Component
⭐ @Service
⭐ @Autowired

Ivi Spring Boot backbone.

🟢 Problem Without Spring

Normal Java lo objects ila create chestam:

class Engine {
    void start() {
        System.out.println("Engine started");
    }
}

class Car {

    Engine engine = new Engine();

    void drive() {
        engine.start();
        System.out.println("Car driving");
    }
}

Problem:

Car class directly Engine object create chesindi

Meaning:

Tight coupling

Car ki Engine change cheyyali ante code modify cheyyali.


🟢 @Component vs @Service

Both same but meaning different.

Annotation	Use
@Component	Generic class
@Service	Business logic
@Repository	Database layer
@Controller	MVC controller
@RestController	REST API controller
