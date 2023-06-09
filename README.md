# Spring-WEB-MVC

# => MVC :-
	-> Full form of MVC is Model View Controller
	-> MVC is design pattern which is used to seperate the application layers i.e. we are able to seperate the UI/presentation layer,
        logical layer and controller layer.
	
 # -> Architecture of MVC :-
	
# 	-> Controller :-
		= Controllers are used to handle the client request
		= Controllers acts/works for both View and Model layer
		= "Servlets" acts as controllers
		
# 	-> Model :-
		= Models are used to provide the data-related logic or business logic
		= "POJO (Plain Old Java Object)" class acts as models
		
# 	-> View :-
		= View represent the UI/presentation layer which is transfered to the client as a response
		= "HTML, JSP etc" acts as view
		
# 		= There are 2 types of views :-
			1. static view (html)
			2. dynamic view (JSP)
			


# => Servlet :-
	= Servlet is a "server side programming technology" which is used to handle the request from the clients
	= Servlets are "Java Program/Page" which are executed on the server
	= Its extention is ".java"


# => JSP :-
	= JSP is a "server side programming technology" which is used to create dynamic web pages
	= JSP contains HTML and JSP tags
	= Its extention is ".jsp"
	
# => MVC Architecture in Advance Java (JDBC, JSP & Servlet) :-
	


# => Terms you should know :-
	1. HTML and its tags
	2. HTTP Protocol
	3. HTTP methods
	4. Difference between GET and POST
	
-----------------------------------------------
# MVC Architecture
![MVC_Architecture_lyst2442](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/1c5f5f10-0dfd-4979-a0cf-d82138b9fbdb)


# MVC Architecture in Advanced JAVA
![MVC_Architecture_in_Advance_Java_lyst5005](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/71de1a77-76ee-472f-9d65-47fd69ef7051)


# Servlet JSP
![Servlet___JSP_lyst6903](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/4baae7df-7264-49e3-be2d-790670be0582)



# program_flow

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/93c4ab62-f4f9-49f9-bd6e-45747a712bea)







# Spring WEB MVC Deep Explanation

# => Spring WEB-MVC :-
	-> Spring WEB-MVC is the java framework which follows the MVC design pattern
	-> It is used to develop flexible and loosly coupled web applications
	
	-> String WEB-MVC architecture :-
		
# 	-> Components in Spring WEB-MVC architecture :-
		1. web.xml
		2. Front Controller
		3. Spring Configuration File
		4. Handler Mapping
		5. Controller
		6. Command Classes
		7. View Resolvers
		8. View
		

# => web.xml :-
	-> web.xml is the "deployment descriptor file" which is the part of every JavaEE application
	-> Some of the responsibilities of web.xml file are :-
		= welcome file configuration
		= servlets configurations
		= session timeout configuration
		= filters configurations
		= listeners configurations
		= context parameters configurations
		= tag libraries configuration
		= error page configurations
		
	-> In Spring WEB-MVC, its main task is to configure the front-controller i.e. DispatcherServlet
	-> We create web.xml file in WEB-INF folder
	
	
# => Front Controller :-
	-> Front Controller is the controller that handles all the client requests and deligates the request to the other components
	-> In Spring WEB-MVC, "DispatcherServlet" acts as front-controller
	
	-> "DispatcherServlet" is the single entry point for client request to spring web application
	-> Flow of "DispatcherServlet" in Spring WEB-MVC
	-> "DispatcherServlet" is the class which is present in "org.springframework.web.servlet" package
	-> Hierarchy of "DispatcherServlet" class :-
	
	
# => Spring Configuration File :-
	-> Spring Configuration File is an XML file which is used to configure :-
		= bean classes
		= handler mapping classes
		= controller classes
		= view resolver classes
	-> The default name of Spring Configuration File is "[servlet-name]-servlet.xml" and its default location is WEB-INF folder
	
	
# => Handler Mapping :-
	-> Handler Mapping is used to map the requests to proper controller (or handler) and returns that controller name to front controller (DispatcherServlet)
	-> For this, Spring WEB-MVC has provided "HandlerMapping" interface and its implemented classes which are as follows :-
		1. BeanNameUrlHandlerMapping
		2. DefaultAnnotationHandlerMapping
		3. SimpleUrlHandlerMapping
		4. ControllerClassNameHandlerMapping
		   etc
	-> These handler mapping classes are present in "org.springframework.web.servlet.handler" package
	
	
# => Controller :-
	-> Controller is the java class which is used to process the request
	-> Its main task is to execute the business logic or to interact with service layer
	-> For controller, Spring WEB-MVC has provided "Controller" interface and its implemented classes which are as follows :-
		1. AbstractController
		2. BaseCommandController
		3. MultiActionController
		4. SimpleFormController
		5. AbstractFormController
		   etc
	-> These controller classes are present in "org.springframework.web.servlet.mvc"
	
	
# => Command Classes :-
	-> Command Classes are normal java bean class or POJO class
	-> It is used to store the form data which is submitted by the client and then this data is available for business logic
	
	
# => View Resolvers :-
	-> View Resolvers are used to resolve the views and return the correct view to the front controller (DispatcherServlet)
	-> For this Spring WEB-MVC has provided "ViewResolver" interface and its implemented classes which are as follows :-
		1. InternalResourseViewResolver
		2. ResourceBundleViewResolver
		3. XmlViewResolver
		4. BeanNameViewResolver
		5. UrlBasedViewResolver
		6. FreeMarkerViewResolver
		7. VelocityViewResolver
		   etc
# 	-> These are classes are present in "org.springframework.web.servlet.view" package
		   
		   
# => View :-
	-> It is the presentation or UI which is send to the client as a response
	-> Some views are HTML, JSP, freemaker, velocity etc
	
	
=================
# Spring WEB MVC Architecture
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/632423a6-a6ad-4b77-b9d2-1929b2fb1eae)


# Dispatcher Servlet working
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/f4077e57-5f2f-418a-9ce7-2fb204763ab1)

# Dispatcher Servlet hierarchy
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/25e5de19-aae0-4f6b-9c15-f8a28d925563)


# Controller  hierarchy
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/9dcff31c-d26b-4122-83c1-d8c225bd43c0)



---------------------------
# Spring WEB MVC

# Spring web mvc program explaination

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/565b0423-1d62-4703-af3f-c813491fc09d)

# spring mvc task

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/54ded0af-9650-40dd-a7bc-66b38b37261a)

---------------------------





# Handler Mapping Classes Controller Classes

# => SimpleUrlHandlerMapping :-
	-> This class is used to map the URL with their respective controllers
	-> The convention is to take the URL and its respective controller id/name, then it will goes to the controller directly
	-> We can this class by 2 ways :-
		1. By prop key
		2. By value
		
		
# => ControllerClassNameHandlerMapping :-
	-> This class is used to generate the URL path mapping from the controller class name
	-> The convention is to take the short name of the controller class (short name will be taken by removing the 'Controller' suffix 
        if it exists and return the lower-case text) and map it with URL leading /
	-> For example :-
		HelloController -> /hello
		HiController -> /hi
	-> It is depricated in latest versions of spring
	
--------------------------
# => AbstractController :-
	-> It is the parent class of all the controllers in spring
	-> It is implemented on the basis of "Template Method" design pattern
	-> It provides some extra features like caching support, enables the filtering of HttpMethods, controls wether it will work with or without HttpSession etc
	-> There are 3 types of AbstractController :-
		1. ParameterizableViewController
		2. BaseCommandController
		3. MultiActionController
		
		
# => ParameterizableViewController :-
	-> This class is used to display web pages without controller i.e. without processing the request
	-> In this case, it is not required to provide any user defined controller class. We can configure the page directly.
       It will take "viewName" property with its corresponding value i.e. view page name, and open the view JSP page
	-> It is mostly used for hyper links
--------------------------------


ParameterizableViewController

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/b6c14edc-d934-4827-b46f-7166739d642e)











# => MultiActionController :-
	-> This is the controller class which allows the multiple requests (URL) to be mapped within one class (controller)
	-> It maps the request (URL) to the method names
	-> It is depricated from the latest versions of spring
	

# => Command Classes :-
	-> Command Classes are normal java bean class or POJO class which is used to store the form data which is submitted by the client
	-> For each request spring will create a separate command object in which all the details/information is collected
	-> For this spring has provided some "Command Controller Classes" :-
		1. BaseCommandController
		2. AbstractCommandController
		3. AbstractFormController
		4. SimpleFormController
		5. AbstractWizardFormController
		
		
# => BaseCommandController :-
	-> It is the base class for all "Command Controller Classes"
	-> It is used to :-
		= create java bean objects
		= validate the content of java beans using validator
		= to transform the object into string or vice versa using custom editors (in the form of PropertyEditors)
	-> It is depricated from the latest versions of spring
	
	
# => AbstractCommandController :-
	-> It is "Command Controller Class" which is used to :-
		= create java bean objects
		= validate the content of java beans using validator
	-> Mostly it is not used to handle the form submission because form functionalities are offers by AbstractFormController in detailed way
	-> It is depricated from the latest versions of spring
	
	
# => AbstractFormController :-
	-> It is the base class of SimpleFormController and AbstractWizardFormController
	-> It is "Form Controller Class" that creates java bean objects for every form request. We can set sessionForm property as true or false 
     if we want the same or new bean instance as per the request
	-> It is depricated from the latest versions of spring
	
	
# => SimpleFormController :-
	-> It is "Form Controller Class" which is used to handle the form data
	-> It provides formView, successView in case of valid form submission and provides validation errors is user enters any wrong data in the form
	-> It is depricated from the latest versions of spring
	
	
# => AbstractWizardFormController :-
	-> A wizard is a step-by-step process that allows the users to input the information in a particular order and in which next steps 
         may depends on the information provided in previous steps. Wizard involves multiple pages
	-> To support wizard, spring has provided one class i.e. AbstractWizardFormController
	-> It allows the users to carry the same command object through the entine flow of web-pages in wizard
	-> There are some actions in case of wizard :-
		= finish
		= cancel
		= page change
	-> It is depricated from the latest versions of spring
	
	
# => NOTE : In spring latest versions (Spring 3.x version) all these classes has been depricated and replaced by annotation-style controller
-----------------------------------

Multi Action Controller


![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/c80ee509-6626-46c2-b19e-3b9ddcbd9685)


Wizard Form

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/4ddb4607-3dd5-4794-860e-54fa67a377f1)









--------------------------
# Spring from tag library View Resolver Classes

# => Spring Form Tag Library :-
	-> Spring form tag library is the set of data-binding tags for handling the form elements when using JSP and Spring WEB MVC.
	-> It is used for creating HTML components, error messages, themes and internationalized messages
	-> It is built-in library which is bundled in "spring-webmvc.jar" and the descriptor is known as "spring-form.tld".
	-> To use these tags, you have to include the tablib i.e. 
		<%@ taglib prefix="form" uri="http://www.springframework.org/tags/form" %>
# 	-> List of tags available are :-
		1. form:form
		2. form:input
		3. form:radiobutton
		4. form:checkbox
		5. form:password
		6. form:select
		7. form:textarea
		8. form:hidden
		   etc
		
--------------

# => View Resolvers commonly used classes are :-
	1. InternalResourseViewResolver (default)
	2. UrlBasedViewResolver
	3. XmlViewResolver
	4. ResourceBundleViewResolver
	
------------------------

# => UrlBasedViewResolver :-
	-> It is an implementation of ViewResolver interface
	-> It directly resolves the view name to the Url
	-> It requires 3 properties :-
		1. prefix
		2. suffix
		3. viewClass
	-> NOTE : If we want to use JstlView class then we have to add 2 jar files i.e.
		1. taglibs-standard-impl-1.2.5
		2. taglibs-standard-spec-1.2.5
		

# => XmlViewResolver :-
	-> It will resolve the view which is defined in xml file
	
	
# => ResourceBundleViewResolver :-
	-> It will resolve the view which is defined in properties file
	
------------------


# Spring Annotation

=> Annotations :-
------------------------

# => @Controller :-
	-> It indicates that a particular class serves the role of controller
	-> It can be applied to the classes
	-> For example :-
		@Controller
		class HelloController
		{
			---------
		}
		
		
# => @RequestMapping :-
	-> It is used to map the requests onto specific handler methods or handler classes
	-> It can applied to the methods and controller classes also
	-> For example :-
		----------------------
		@Controller
		public class HelloController
		{
			//@RequestMapping("/aaa")
			
			//@RequestMapping(value="/aaa")
			
			//@RequestMapping(value={"/aaa","/bbb","/ccc"})
			
			//@RequestMapping(value="/aaa", method=RequestMethod.GET)
			
			@RequestMapping(value="/aaa", method= {RequestMethod.GET, RequestMethod.POST})
			public String m1()
			{
				----body----
				return "hello";
			}
		}
		------------------------
		<form action="aaa/bbb" method="post">
			<input type="submit" value="Click Me" />
		</form>
		
		@Controller
		@RequestMapping("/aaa")
		public class HelloController
		{
			@RequestMapping("/bbb")
			public String m1()
			{
				----body-----
				return "hello";
			}
		}
		
		
# => @RequestParam :-
	-> It is used to fetch the values of the parameter in the form request object
	-> It is used in mthod parameter
	-> For example :-
		----------------------------
		@Controller
		public class HelloController
		{
			@RequestMapping("/aaa")
			public String m1(@RequestParam("name1") String myname)
			{
				//String myname = request.getParameter("name1");
				System.out.println("hello controller....");
				return "hello";
			}
		}
		----------------------------
		@Controller
		public class HelloController
		{
			@RequestMapping("/aaa")
			public String m1(
					@RequestParam("name1") String myname,
					@RequestParam("email1") String myemail,
					@RequestParam("pass1") String mypass
				)
			{
				System.out.println("hello : "+myname+", your email id is "+myemail);
				return "hello";
			}
		}
		----------------------------
		@Controller
		public class HelloController
		{
			@RequestMapping("/aaa")
			public String m1(@RequestParam(name="name1") String myname)
			{
				System.out.println("hello controller....");
				return "hello";
			}
		}
		----------------------------
		@Controller
		public class HelloController
		{
			@RequestMapping("/aaa")
			public String m1(@RequestParam(name="city1", required = false, defaultValue = "Delhi") String mycity)
			{
				System.out.println("hello controller....");
				return "hello";
			}
		}
		----------------------------
		
==============

# => Model :-
	-> In MVC framework, M stands for Model which is used to store and process the data
	-> For this, spring framework has provided one interface i.e. Model which is present in "org.springframework.ui" package
	-> The data stored in the model can be anything i.e. strings, objects, data from database etc
	
===================





# Spring Annotations Request and Session Scope Intro 

# => @ModelAttribute :-
	-> It binds the method parameter or method return value to a named model-attribute and then can be used in the web view.
	-> It can be used with method parameter or before method
	-> For example :-
		
		public String register(@ModelAttribute("ma_student") Student std, Model model)
		{
			--------
		}
		
		--------------------------------------------
		
		@ModelAttribute
		public void modelData(Model model)
		{
			System.out.println("modelData() method executed");
			
			model.addAttribute("m_name", "deepak");
			model.addAttribute("m_email", "deepak@gmail.com");
		}
		
		--------------------------------------------
		
		@ModelAttribute("ma_name")
		public String modelData()
		{
			System.out.println("modelData() method executed");
			return "Deepak Panwar";
		}
		
		--------------------------------------------
    
    
    
    
    
    
    
    
    
    
#  => @SessionAttributes
	-> It is an annotation provided by spring to store the data in session area
	-> We can set any type of data in SessionAttributes
	-> If we want to delete session object :-
		= We have to create SessionStatus reference
		= Then we have to call sessionStatus.setComplete() method
	-> It is declared at class level
	-> For example :-
		@Controller
		@SessionAttributes("------")
		public class FirstController
		{
			------------
		}
		
# 	-> NOTE :
		= Be careful while using @SessionAttributes because it may be possible that first developer can delete the session object which is used by another developer
		= For permanent session attributes, e.g. a user authentication object, use the traditional session.setAttribute method instead
	
# program flow
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/9dc75f43-aeb0-4cfe-9a22-61967794ab40)






# Spring MVC Validation

# => JCP :-
	-> Full Form of JCP is "Java Community Process"
	-> It is simply a process that allows interested parties (individual or organization) to develop standard technical specifications for java technology
	-> It was established in 1998
	-> It is membership community and anyone can join it from "www.jcp.org" website
	
	
# => JSR :-
	-> Full form of JSR is "Java Specification Request"
	-> It is a formal, open standard document proposal that is made by the parties (individual or organization) to the JCP
	-> It contains proposed changes, additions or improvements to the Java Technology Specifications
	-> Spring MVC Framework supports JSR-303 or JSR-349 or JSR-380 specifications by default for validations
	
	
# => Validations :-
	-> Validations are the restrictions provided to the client while filling the form so that data entered by the client is valid
	-> There are 2 types of validations :-
		1. Client Side Validations
			= technologies used for client side validations are JavaScipt, VB Script etc
		2. Server Side Validations
			= technologies used server side validations are JSP, Servlet, Spring, Webservices etc


# => Spring MVC Validations :-
	-> We can achieve Spring MVC Validations by 2 ways :-
		1. Using pre-defined spring provided classes (Errors) [org.springframework.validations]
		2. Java Bean Validations API (JSR-303 or JSR-349 or JSR-380)
		
		
# => Java Bean Validations API :-
	-> It contains "Java Bean Validations Annotations" and "Hibernate Validator Annotations" for validations in spring mvc framework
	-> NOTE : Hibernate is the vendor which implements JSR
	-> It is very famous API for validations
	
# 	-> Annotations used are :-
		1. @NotNull
		2. @Min
		3. @Max
		4. @Size
		5. @Pattern
		6. @Past
		   etc
		
		7. @NotEmpty
		8. @NotBlank
		9. @Email
		10. @Length
		11. @Range
			etc
      
# JCP and JSR
		
    ![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/98ae9cf9-c2c6-4272-8ca1-f24c798609f8)







# Spring MVC Validation

# Spring Validation Interceptors

# => What is difference between @NotNull, @NotEmpty and @NotBlank :-
	= @NotNull :- Objects, Arrays, Collections, Map, CharSequence should not be null but can be empty
	= @NotEmpty :- Objects, Arrays, Collections, Map, CharSequence should not be null and size should be greater then 0
	= @NotBlank :- The string should not be null and the trimmed length should be greater then 0
	
	
=> @Min and @Max :-
	= They are used for integers
	
=> @Past and @Future :-
	= They are used for Date (java.util)
	
=> What is difference between @Size and @Length :-
	= @Size is a Bean Validation annotation that validates that the associated 
            String has a value whose length is bounded by the minimum and maximum values.
	= @Length is a Hibernate-specific annotation and has the same meaning as @Size
	
=> @Range :-
	= It can be used for integer values in which we specify min and max values
	
=============

# => Spring Interceptors :-
	-> If we want pre-processing and post-processing service for any controller class then we have to use spring interceptors
	-> For example, we use spring interceptors in logging services, authentication services, validation services, encryption/decryption services etc
	
	-> To create interceptors spring has provided one interface i.e. "HandlerInterceptor"
	-> HandlerInterceptor contains 3 methods :-
		1. preHandle()
		2. postHandle()
		3. afterCompletion()
		
==============

Interceptors 
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/f6905ea0-6016-4d58-bb15-413260b7f11a)

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/3a177941-a780-436f-8781-bb31e948d9aa)














# => Error and Exception Handling in Spring MVC :-
	-> Handling any unwanted event in the program
	-> In spring MVC we can handle the exception as follows :-
		1. by web.xml file
		2. by pre-defined class (SimpleMappingExceptionResolver)
		3. by annotations (@ControllerAdvice & @ExceptionHandler)
		





# => Upload & Download File in Spring MVC :-
	-> 1. Provide enctype="multipart/form-data" in form tag
			= enctype specifies how form-data should be encoded before sending it to the server.
			= enctype can be used only with post method, not with get method
	   2. Download 2 jar files for upload and download :-
			= commons-fileupload.jar
			= commons-io.jar
	   3. Spring has provided one interface i.e. MultipartFile to get the file from the form
	   4. Get the file and write it in the folder
	   5. Configure CommonsMultipartResolver class in spring configuration file
     
     
     
     ![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/25125e6f-1e1e-4c45-91d9-9542963bb645)









# => JSP Include :-
	-> It is used to include one jsp page into another jsp page
	-> <jsp:include page="page-name.jsp" />


# => Spring MVC Tiles :-
	-> It is used to manage the layout of Spring MVC application
	-> For this Spring provides an integration with "Apache Tiles Framework"
	
# 	-> Advantages :-
		1. Resuability
			= Wwe can reuse the web component i.e. header, menubar, footer etc
		2. Easy to change the layout
			= We can easily change the layout from one template to another template
		3. Centralized Control
			= We can control the layout of the pages from a single template page


template 1
![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/90bfc31b-e2fe-4eef-8ed9-9f9bf7fcb30f)

template 2

![image](https://github.com/Nishita-Maheshwari/Spring-WEB-MVC/assets/47790697/a802e3eb-d009-4cd2-ae40-79815a6229f8)














# => Spring MVC using Java Configurations :-
	
	-> Annotations used are :-
	
		1. @Configuration :-
			-> It tells spring that this is a configuration class and it needs to be consider when the application loads
			-> It indicates that the class has @Bean defination methods
			
		2. @Bean :-
			-> It is used to mark the method as one that creates a bean and spring will add it to the context so that it can be used
			-> The return type of the method defines the type of bean that is created
			-> It is used in replacement of <bean> tag in spring configuration file
			
		3. @ComponentScan :-
			-> It will take the base package name and it will scan the packages for controllers, services, components, repositories etc
			-> It is used in replacement of <context:component-scan base-package="in.sp.controllers" />
			
		4. @EnableWebMvc :-
			-> It enables default Spring MVC configurations and register Spring MVC components expected by DispatcherServlet
			-> It is used in replacement of <mvc:annotation-driven/>
			
	-> Classes & Interfaces used are :-
	
		1. AbstractAnnotationConfigDispatcherServletInitializer <class>
		2. WebApplicationInitializer <interface>
		
====================
