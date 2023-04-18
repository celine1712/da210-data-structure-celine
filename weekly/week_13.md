# Planning for Week 13

## High Level Topic Summary

  - HTTP
    - Introduction to HTTP
    - `GET`, `POST` Requests
    - Request and Response Headers
  - `requests` module
  - Integrating Requests with Processing
    - Encodings
    - `BytesIO` and `StringIO`

## Readings for the week

Day        | Reading      | Reading Questions
:--------- |:-------------|:----------------------------------
Monday     | Sections 20.1-20.2 | 20.4, 20.8
Tuesday    | Sections 19.3, 20.3 | 20.25, 20.33
Wednesday  | Section 21.1 | 21.4
Friday     | Sections 21.2-21.4 | 21.17, 21.19, 21.28, 21.32, 21.40, 21.46

## Progression

This week, we will explore the foundations we need to understand the data-sources dimension of this course.  Our focus will be on HTTP, including the structure of an HTTP request and how we can build one in Python.  Finally, we'll look at processing the body of an HTTP response.

Monday:  We will begin our exploration of HTTP, which is the dominant protocol of the internet, and provides a backbone for many popular networking libraries and APIs.

Tuesday: We will continue exploring HTTP, focusing on different types of requests.  We will consider the HTTP method (`GET` and `POST`), the values of header key-value pairs, augmentation of the resource path with query string key-value pairs and, for `POST` requests, including a body that contains information for the request.

Wednesday: We will begin our discussion of HTTP responses, for which we need to be able to understand and accomodate encodings, get meta-information about the response through its headers, and process the body of the response.

Friday: We will discuss how to transform the body of an HTTP response into the data formats discussed in this course (CSV, JSON, XML).

---

## Projected Homework

HW | Day Assigned  | Day Due (by 11:59pm) | Contents
:--|:--------|:--------|:------------
[HW_5.a](../hw/HW_5.a/README.md) | Monday (4/17) | Wednesday (4/19) | HTTP fundamentals
HW_5.b | Wednesday (4/19) | Friday (4/21) | encodings
HW_5.c | Friday (4/21) | Monday (4/24) | CSV and XML request processing

## Tuesday Software Lab

In the [thirteenth software lab](../sw_lab/lab_13/README.md), we'll explore Python's `requests` module (`GET` and `POST`).