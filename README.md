# lab10-cicd
# Canary Deployment Strategy

Our application would use a Canary Deployment strategy.

## Process
1. Deploy new version to 5% of users
2. Monitor system performance
3. Check error rates and response times
4. If stable, gradually increase traffic:
   - 20%
   - 50%
   - 100%

## Monitoring

The canary deployment would be monitored using:

- Error logs
- Application response time
- Failed requests
- User feedback

If error rate increases, deployment is rolled back automatically.