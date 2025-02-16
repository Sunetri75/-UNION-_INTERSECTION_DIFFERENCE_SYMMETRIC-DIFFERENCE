# -UNION-_INTERSECTION_DIFFERENCE_SYMMETRIC-DIFFERENCE
# Define two sets
E = {0, 2, 4, 6, 8}
N = {1, 2, 3, 4, 5}

# Perform set operations
union_set = E | N 
intersection_set = E & N 
difference_set = E - N  
symmetric_difference_set = E ^ N 

# Print the results
print("Union of E and N is", list(union_set))  
print("Intersection of E and N is", list(intersection_set))
print("Difference of E and N is", list(difference_set))  
print("Symmetric difference of E and N is", list(symmetric_difference_set)) 
