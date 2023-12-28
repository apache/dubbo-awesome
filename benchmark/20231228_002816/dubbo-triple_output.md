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
# Warmup Iteration   1: 5.675 ops/ms
# Warmup Iteration   2: 12.393 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 13.015 ops/ms
Iteration   2: 12.991 ops/ms
Iteration   3: 12.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.991 ±(99.9%) 0.434 ops/ms [Average]
  (min, avg, max) = (12.968, 12.991, 13.015), stdev = 0.024
  CI (99.9%): [12.558, 13.425] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 8.681 ops/ms
# Warmup Iteration   2: 13.237 ops/ms
# Warmup Iteration   3: 13.315 ops/ms
Iteration   1: 13.513 ops/ms
Iteration   2: 13.407 ops/ms
Iteration   3: 13.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.428 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (13.365, 13.428, 13.513), stdev = 0.076
  CI (99.9%): [12.033, 14.824] (assumes normal distribution)


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
# Warmup Iteration   1: 8.024 ops/ms
# Warmup Iteration   2: 12.827 ops/ms
# Warmup Iteration   3: 13.381 ops/ms
Iteration   1: 13.184 ops/ms
Iteration   2: 13.403 ops/ms
Iteration   3: 13.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.267 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (13.184, 13.267, 13.403), stdev = 0.119
  CI (99.9%): [11.104, 15.430] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.062 ops/ms
# Warmup Iteration   2: 10.746 ops/ms
# Warmup Iteration   3: 10.788 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.849 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.767 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (10.718, 10.767, 10.849), stdev = 0.071
  CI (99.9%): [9.463, 12.071] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (2.444, 2.471, 2.489), stdev = 0.024
  CI (99.9%): [2.042, 2.900] (assumes normal distribution)


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.393 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.396 ±(99.9%) 0.004 ms/op
Iteration   1: 2.332 ±(99.9%) 0.005 ms/op
Iteration   2: 2.342 ±(99.9%) 0.004 ms/op
Iteration   3: 2.372 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.349 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.332, 2.349, 2.372), stdev = 0.021
  CI (99.9%): [1.963, 2.735] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.429 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.421, 2.429, 2.437), stdev = 0.008
  CI (99.9%): [2.283, 2.575] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.517 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.005 ms/op
Iteration   1: 2.908 ±(99.9%) 0.005 ms/op
Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
Iteration   3: 2.917 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.917 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.908, 2.917, 2.924), stdev = 0.008
  CI (99.9%): [2.767, 3.066] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  7.060 ms/op
                 createUser·p0.9999: 13.502 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  7.547 ms/op
                 createUser·p0.9999: 11.860 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  7.621 ms/op
                 createUser·p0.9999: 9.945 ms/op
                 createUser·p1.00:   10.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391042
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 197541 
    [ 2.500,  3.750) = 188971 
    [ 3.750,  5.000) = 3435 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.828 ms/op
     p(99.9000) =      7.536 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.993 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.392 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.336 ±(99.9%) 0.005 ms/op
Iteration   1: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 13.248 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.382 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.020 ms/op
                 existUser·p0.9999: 11.698 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.382 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.782 ms/op
                 existUser·p0.999:  7.829 ms/op
                 existUser·p0.9999: 10.217 ms/op
                 existUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402370
  mean =      2.384 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 213989 
    [ 2.500,  3.750) = 185206 
    [ 3.750,  5.000) = 2385 
    [ 5.000,  6.250) = 250 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      7.648 ms/op
     p(99.9900) =     12.457 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.006 ms/op
Iteration   1: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  6.990 ms/op
                 getUser·p0.9999: 15.335 ms/op
                 getUser·p1.00:   15.548 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.951 ms/op
                 getUser·p0.999:  8.638 ms/op
                 getUser·p0.9999: 12.778 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.408 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  5.956 ms/op
                 getUser·p0.9999: 10.568 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 396174
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 205502 
    [ 2.500,  3.750) = 186393 
    [ 3.750,  5.000) = 3183 
    [ 5.000,  6.250) = 501 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.786 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     13.355 ms/op
     p(99.9990) =     15.483 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.008 ms/op
Iteration   1: 2.890 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.736 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   5.333 ms/op
                 listUser·p0.999:  8.542 ms/op
                 listUser·p0.9999: 10.287 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 2.937 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.554 ms/op
                 listUser·p0.9999: 10.974 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   3: 2.903 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.173 ms/op
                 listUser·p0.9999: 11.550 ms/op
                 listUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 329624
  mean =      2.910 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 209 
    [ 1.250,  2.500) = 107621 
    [ 2.500,  3.750) = 188309 
    [ 3.750,  5.000) = 27626 
    [ 5.000,  6.250) = 4684 
    [ 6.250,  7.500) = 573 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 227 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     11.775 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.991 ± 0.434  ops/ms
ClientPb.existUser                       thrpt       3  13.428 ± 1.395  ops/ms
ClientPb.getUser                         thrpt       3  13.267 ± 2.163  ops/ms
ClientPb.listUser                        thrpt       3  10.767 ± 1.304  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.429   ms/op
ClientPb.existUser                        avgt       3   2.349 ± 0.386   ms/op
ClientPb.getUser                          avgt       3   2.429 ± 0.146   ms/op
ClientPb.listUser                         avgt       3   2.917 ± 0.149   ms/op
ClientPb.createUser                     sample  391042   2.453 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.797           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.486           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.828           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.536           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  402370   2.384 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.636           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  396174   2.421 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.743           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.966           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.786           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.947           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.355           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.548           ms/op
ClientPb.listUser                       sample  329624   2.910 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.839           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.911           ms/op
