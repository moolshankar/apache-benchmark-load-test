# apache-benchmark-load-test

ab -n Request-Count -c Concurrency-count "<Target-Url>" | grep "Requests"

ab -n 10000 -c 100 "http://localhost:8080/test" | grep "Requests"
