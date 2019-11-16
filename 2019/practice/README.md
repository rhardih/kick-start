# Notes

This snippet can add a *large* test case to the test input:

```bash
ruby -e 'puts 5000000; puts (Array.new(5000000) { 1 + rand(9) }).join' >> mural.test.in
```

Remember to increment the first line value of T.
