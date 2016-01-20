package com.gitrdone;

import java.io.Serializable;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;
import javax.persistence.Lob;

@Entity
public class Volunteers implements Serializable {
	
	@Id
	@GeneratedValue (strategy = GenerationType.AUTO)
	String FirstName;
	String LastName;
	String Email;
	String Phone;
	@Lob
	String Comments;
	
	public Volunteers (){}
	
	public Volunteers(String FirstName, String LastName,
			String Email, String Phone) {
		this.FirstName = FirstName;
		this.LastName = LastName;
		this.Email = Email;
		this.Phone = Phone;
		this.Comments = Comments;
		
	}

	public String getFirstName() {
		return FirstName;
	}

	public void setFirstName(String firstName) {
		FirstName = firstName;
	}

	public String getLastName() {
		return LastName;
	}

	public void setLastName(String lastName) {
		LastName = lastName;
	}

	public String getEmail() {
		return Email;
	}

	public void setEmail(String email) {
		Email = email;
	}

	public String getPhone() {
		return Phone;
	}

	public void setPhone(String phone) {
		Phone = phone;
	}

	public String getComments() {
		return Comments;
	}

	public void setComments(String comments) {
		Comments = comments;
	}

}
