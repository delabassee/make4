# About

{{site.title}} Server is the open source Java EE Reference Implementation. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor ut labore et dolore aliqua. Ut enim ad minim veniam, quis exercitation ullamco laboris nisi ut aliquip.
  
  
# Latest News

## April 1st, 2017 - Java.net migration! ##

All the {{site.title}} assets has been moved from Java.net to a new location.

## April 10th, 2017 - JAX-RS PATCH support (client API) ##

PATCH support has been added to JAX-RS API 2.1 in ms06, see [here](https://java.net/projects/jax-rs-spec/lists/users/archive/2017-04/message/40).

```java
/**
 * Indicates that the annotated method responds to HTTP PATCH requests.
 *
 * @author Pavel Bucek (pavel.bucek at oracle.com)
 * @see HttpMethod
 * @since 2.1
 */
@Target({ElementType.METHOD})
@Retention(RetentionPolicy.RUNTIME)
@HttpMethod(HttpMethod.GET)
@Documented
public @interface PATCH {
}
```


