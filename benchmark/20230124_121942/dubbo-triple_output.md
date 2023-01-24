# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.006 ops/ms
# Warmup Iteration   2: 2.580 ops/ms
# Warmup Iteration   3: 5.068 ops/ms
Iteration   1: 5.622 ops/ms
Iteration   2: 5.815 ops/ms
Iteration   3: 5.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.695 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (5.622, 5.695, 5.815), stdev = 0.105
  CI (99.9%): [3.779, 7.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.402 ops/ms
# Warmup Iteration   2: 4.267 ops/ms
# Warmup Iteration   3: 5.512 ops/ms
Iteration   1: 6.074 ops/ms
Iteration   2: 6.020 ops/ms
Iteration   3: 6.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.086 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (6.020, 6.086, 6.164), stdev = 0.073
  CI (99.9%): [4.758, 7.415] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 4.295 ops/ms
# Warmup Iteration   3: 5.555 ops/ms
Iteration   1: 5.793 ops/ms
Iteration   2: 5.806 ops/ms
Iteration   3: 5.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.832 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (5.793, 5.832, 5.896), stdev = 0.056
  CI (99.9%): [4.813, 6.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.432 ops/ms
# Warmup Iteration   2: 4.181 ops/ms
# Warmup Iteration   3: 4.930 ops/ms
Iteration   1: 4.937 ops/ms
Iteration   2: 5.131 ops/ms
Iteration   3: 5.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.088 ±(99.9%) 2.461 ops/ms [Average]
  (min, avg, max) = (4.937, 5.088, 5.197), stdev = 0.135
  CI (99.9%): [2.627, 7.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 20.371 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.508 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.094 ±(99.9%) 0.013 ms/op
Iteration   1: 5.885 ±(99.9%) 0.014 ms/op
Iteration   2: 5.536 ±(99.9%) 0.016 ms/op
Iteration   3: 5.521 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.647 ±(99.9%) 3.765 ms/op [Average]
  (min, avg, max) = (5.521, 5.647, 5.885), stdev = 0.206
  CI (99.9%): [1.882, 9.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 18.040 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.494 ±(99.9%) 0.007 ms/op
Iteration   1: 5.364 ±(99.9%) 0.009 ms/op
Iteration   2: 5.377 ±(99.9%) 0.009 ms/op
Iteration   3: 5.274 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.339 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (5.274, 5.339, 5.377), stdev = 0.056
  CI (99.9%): [4.317, 6.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 20.401 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.904 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.452 ±(99.9%) 0.011 ms/op
Iteration   1: 5.524 ±(99.9%) 0.009 ms/op
Iteration   2: 5.625 ±(99.9%) 0.014 ms/op
Iteration   3: 5.493 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.547 ±(99.9%) 1.256 ms/op [Average]
  (min, avg, max) = (5.493, 5.547, 5.625), stdev = 0.069
  CI (99.9%): [4.292, 6.803] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.583 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 8.395 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.581 ±(99.9%) 0.016 ms/op
Iteration   1: 6.505 ±(99.9%) 0.020 ms/op
Iteration   2: 6.834 ±(99.9%) 0.022 ms/op
Iteration   3: 6.493 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.611 ±(99.9%) 3.537 ms/op [Average]
  (min, avg, max) = (6.493, 6.611, 6.834), stdev = 0.194
  CI (99.9%): [3.074, 10.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.259 ±(99.9%) 0.331 ms/op
# Warmup Iteration   2: 7.971 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 5.876 ±(99.9%) 0.027 ms/op
Iteration   1: 5.617 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.572 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 28.659 ms/op
                 createUser·p1.00:   30.245 ms/op

Iteration   2: 5.575 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   8.241 ms/op
                 createUser·p0.99:   11.338 ms/op
                 createUser·p0.999:  17.906 ms/op
                 createUser·p0.9999: 29.139 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 5.666 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.176 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  27.623 ms/op
                 createUser·p0.9999: 31.415 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170724
  mean =      5.619 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 63784 
    [ 5.000,  7.500) = 93081 
    [ 7.500, 10.000) = 10566 
    [10.000, 12.500) = 2231 
    [12.500, 15.000) = 595 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     22.422 ms/op
     p(99.9900) =     30.240 ms/op
     p(99.9990) =     32.010 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 18.027 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 6.098 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.359 ±(99.9%) 0.023 ms/op
Iteration   1: 5.433 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   7.078 ms/op
                 existUser·p0.95:   8.331 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  22.381 ms/op
                 existUser·p0.9999: 25.704 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 5.233 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.928 ms/op
                 existUser·p0.999:  17.552 ms/op
                 existUser·p0.9999: 28.340 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 5.247 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.963 ms/op
                 existUser·p0.99:   11.305 ms/op
                 existUser·p0.999:  27.895 ms/op
                 existUser·p0.9999: 36.962 ms/op
                 existUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181024
  mean =      5.303 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 103879 
    [ 5.000,  7.500) = 64925 
    [ 7.500, 10.000) = 9169 
    [10.000, 12.500) = 1971 
    [12.500, 15.000) = 572 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     21.200 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     37.368 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.946 ±(99.9%) 0.360 ms/op
# Warmup Iteration   2: 7.228 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.789 ±(99.9%) 0.027 ms/op
Iteration   1: 5.704 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.277 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.471 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   13.599 ms/op
                 getUser·p0.999:  23.031 ms/op
                 getUser·p0.9999: 27.550 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   2: 5.349 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.593 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.627 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  13.586 ms/op
                 getUser·p0.9999: 28.050 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 5.398 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   10.617 ms/op
                 getUser·p0.999:  24.473 ms/op
                 getUser·p0.9999: 28.025 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174974
  mean =      5.479 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 77642 
    [ 5.000,  7.500) = 85591 
    [ 7.500, 10.000) = 8591 
    [10.000, 12.500) = 1979 
    [12.500, 15.000) = 557 
    [15.000, 17.500) = 302 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      2.277 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     27.968 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.718 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.932 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.442 ±(99.9%) 0.026 ms/op
Iteration   1: 6.327 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  27.311 ms/op
                 listUser·p0.9999: 36.045 ms/op
                 listUser·p1.00:   36.504 ms/op

Iteration   2: 6.298 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  28.585 ms/op
                 listUser·p0.9999: 33.388 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   3: 6.327 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  25.788 ms/op
                 listUser·p0.9999: 34.206 ms/op
                 listUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151869
  mean =      6.317 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 8283 
    [ 5.000,  7.500) = 123551 
    [ 7.500, 10.000) = 15346 
    [10.000, 12.500) = 3443 
    [12.500, 15.000) = 757 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.921 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      7.930 ms/op
     p(95.0000) =      9.142 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     27.829 ms/op
     p(99.9900) =     34.394 ms/op
     p(99.9990) =     36.368 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.695 ± 1.916  ops/ms
ClientPb.existUser                       thrpt       3   6.086 ± 1.329  ops/ms
ClientPb.getUser                         thrpt       3   5.832 ± 1.019  ops/ms
ClientPb.listUser                        thrpt       3   5.088 ± 2.461  ops/ms
ClientPb.createUser                       avgt       3   5.647 ± 3.765   ms/op
ClientPb.existUser                        avgt       3   5.339 ± 1.021   ms/op
ClientPb.getUser                          avgt       3   5.547 ± 1.256   ms/op
ClientPb.listUser                         avgt       3   6.611 ± 3.537   ms/op
ClientPb.createUser                     sample  170724   5.619 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.249           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.305           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.422           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.240           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  181024   5.303 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.393           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.816           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.020           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.223           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.421           ms/op
ClientPb.getUser                        sample  174974   5.479 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.277           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.914           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.979           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.452           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.968           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  151869   6.317 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.921           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.930           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.142           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.091           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.829           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.394           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.504           ms/op
