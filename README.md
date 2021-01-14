# directory-path


Content of `solutions/default/main.tf` :

```
  
module "two" {
   # Correct directory path
   #source = "../../modules/pet-null/v1.0.0"
   
   # Wrong directory path
   source = "../../../modules/pet-null/v1.0.0"
}

```
