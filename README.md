1,"Tinto","2013",4.9,58,90,200,995,3,0,0,0

https://memorynotfound.com/unit-test-spring-mvc-rest-service-junit-mockito/#unit-test-http-get-path-variable


https://java2blog.com/spring-boot-spring-security-example/


private MockMvc mvc;

	@Before
	public void setup() {
		mvc = MockMvcBuilders
				.webAppContextSetup(context)
				.apply(springSecurity()) (1)
				.build();
	}
