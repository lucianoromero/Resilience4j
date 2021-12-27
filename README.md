# Resilience4j
Repositório com exemplo de utilização do pacote Resilience4j, com os principais recurso.
****
Resilience4j é uma biblioteca leve de tolerância a falhas inspirada na Hystrix, da Netflix.<br />
Documentação oficial: https://resilience4j.readme.io/ <br />
****
**Principais recursos:**
- **Bulkhead** <br />
Docs: https://resilience4j.readme.io/docs/bulkhead <br />
Outros: https://reflectoring.io/bulkhead-with-resilience4j/ <br />

- **CircuitBreaker** <br />
Docs: https://resilience4j.readme.io/docs/circuitbreaker <br />
Outros: https://reflectoring.io/circuitbreaker-with-resilience4j/ <br />

- **RateLimit** <br />
Docs: https://resilience4j.readme.io/docs/ratelimiter <br />                                                                                                                 Outros: https://reflectoring.io/rate-limiting-with-resilience4j/

- **Retry** <br />                                                                                                                                                                Docs: https://resilience4j.readme.io/docs/retry <br />	                                                                                                                    Outros: https://reflectoring.io/retry-with-resilience4j/	 <br />	 

 - **TimeLimiter** <br />                                                                                                                                                          Docs: https://resilience4j.readme.io/docs/timeout  <br />                                                                                                                  Outros: https://reflectoring.io/time-limiting-with-resilience4j/ <br />

****
Slide apresentando os principais recursos do pacote: <br />
https://github.com/lucianoromero/Resilience4j/blob/main/Slides/resilience4j-v1.pdf <br />
****
O pacote Resilence4j, depende das seguintes dependência: 
```
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-aop</artifactId>
		</dependency>
		<!-- Resilience4j -->
		<dependency>
			<groupId>io.github.resilience4j</groupId>
			<artifactId>resilience4j-spring-boot2</artifactId>
			<version>LATEST</version>
		</dependency>
```
