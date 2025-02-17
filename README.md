# React Router v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6. The problem lies in how nested routes are defined and accessed.

## Problem

The `ContactDetails` component fails to render when navigating to `/contact/details` because the nesting structure needs to be correctly defined.

## Solution

The solution involves ensuring that nested routes are properly defined within their parent routes, allowing React Router to correctly match the URL path.
