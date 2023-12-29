# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.055 ops/ms
# Warmup Iteration   2: 12.232 ops/ms
# Warmup Iteration   3: 12.356 ops/ms
Iteration   1: 12.500 ops/ms
Iteration   2: 12.661 ops/ms
Iteration   3: 12.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.670 ±(99.9%) 3.191 ops/ms [Average]
  (min, avg, max) = (12.500, 12.670, 12.849), stdev = 0.175
  CI (99.9%): [9.479, 15.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.383 ops/ms
# Warmup Iteration   2: 13.103 ops/ms
# Warmup Iteration   3: 12.934 ops/ms
Iteration   1: 13.072 ops/ms
Iteration   2: 13.121 ops/ms
Iteration   3: 13.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.116 ±(99.9%) 0.760 ops/ms [Average]
  (min, avg, max) = (13.072, 13.116, 13.154), stdev = 0.042
  CI (99.9%): [12.355, 13.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 12.432 ops/ms
# Warmup Iteration   3: 12.562 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.816 ops/ms
Iteration   3: 12.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.689 ±(99.9%) 3.317 ops/ms [Average]
  (min, avg, max) = (12.480, 12.689, 12.816), stdev = 0.182
  CI (99.9%): [9.371, 16.006] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.555 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.535 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.504 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.517 ±(99.9%) 0.479 ops/ms [Average]
  (min, avg, max) = (10.499, 10.517, 10.547), stdev = 0.026
  CI (99.9%): [10.037, 10.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.573 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.535, 2.553, 2.573), stdev = 0.019
  CI (99.9%): [2.206, 2.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.406 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
Iteration   3: 2.402 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.402, 2.420, 2.437), stdev = 0.018
  CI (99.9%): [2.096, 2.744] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.467, 2.476, 2.491), stdev = 0.013
  CI (99.9%): [2.231, 2.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.005 ms/op
Iteration   1: 2.966 ±(99.9%) 0.004 ms/op
Iteration   2: 2.962 ±(99.9%) 0.004 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.039 ms/op [Average]
  (min, avg, max) = (2.962, 2.964, 2.966), stdev = 0.002
  CI (99.9%): [2.925, 3.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  10.575 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  10.198 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.613 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379379
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 183347 
    [ 2.500,  3.750) = 192437 
    [ 3.750,  5.000) = 2814 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.661 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     19.674 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.326 ms/op
                 existUser·p0.999:  6.609 ms/op
                 existUser·p0.9999: 13.496 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.414 ms/op
                 existUser·p0.999:  7.385 ms/op
                 existUser·p0.9999: 12.580 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  7.515 ms/op
                 existUser·p0.9999: 11.010 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393070
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 192917 
    [ 2.500,  3.750) = 196644 
    [ 3.750,  5.000) = 2651 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      7.091 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.857 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  7.013 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  9.493 ms/op
                 getUser·p0.9999: 13.578 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  5.145 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382709
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 188257 
    [ 2.500,  3.750) = 189932 
    [ 3.750,  5.000) = 3586 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     13.349 ms/op
     p(99.9990) =     14.126 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.695 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
Iteration   1: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.460 ms/op
                 listUser·p0.999:  9.040 ms/op
                 listUser·p0.9999: 10.464 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.466 ms/op
                 listUser·p0.9999: 12.016 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.270 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317217
  mean =      3.024 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 87753 
    [ 2.500,  3.750) = 190203 
    [ 3.750,  5.000) = 32405 
    [ 5.000,  6.250) = 5609 
    [ 6.250,  7.500) = 501 
    [ 7.500,  8.750) = 158 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.752 ms/op
     p(99.9990) =     12.642 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.670 ± 3.191  ops/ms
ClientPb.existUser                       thrpt       3  13.116 ± 0.760  ops/ms
ClientPb.getUser                         thrpt       3  12.689 ± 3.317  ops/ms
ClientPb.listUser                        thrpt       3  10.517 ± 0.479  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.347   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.324   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.245   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.039   ms/op
ClientPb.createUser                     sample  379379   2.528 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.841           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.336           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.923           ms/op
ClientPb.existUser                      sample  393070   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.001           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.829           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  382709   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.595           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.349           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  317217   3.024 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.953           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.752           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
