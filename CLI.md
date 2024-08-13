node cli/main.js generate   --output-cloudformation "cloudformation.yml"   --output-terraform "terraform.hcl"   --output-raw-data "debug.json"   --search-filter "myapp"   --exclude-services "CloudWatch,KMS"   --sort-output

New and improved way, instead of using former 2, just use cli/main.js
node cli/main.js generate   --output-cloudformation "cloudformation.yml"   --output-terraform "terraform.hcl"   --output-raw-data "debug.json"   --search-filter "myapp"   --exclude-services "CloudWatch,KMS"   --sort-output