### Delete all keys with certain pattern
`redis-cli --scan --pattern users:* | xargs redis-cli unlink`
