package com.yape;

import org.springframework.beans.factory.annotation.Value;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class ServiceEndPoint {

	@Value("${name:NA}")
	private String name;
	
	@Value("${message:NA}")
	private String message;
	
	
	@GetMapping
	public String listEndPoint() {
		StringBuilder sb=new StringBuilder();
		sb.append("Name:").append(name).append("/n/n");
		sb.append("Message:").append(message).append("/n/n");
		
		return sb.toString();
	}
}
