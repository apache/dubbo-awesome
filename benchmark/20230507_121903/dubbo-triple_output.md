# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.008 ops/ms
# Warmup Iteration   2: 2.391 ops/ms
# Warmup Iteration   3: 5.050 ops/ms
Iteration   1: 5.746 ops/ms
Iteration   2: 6.109 ops/ms
Iteration   3: 6.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.963 ±(99.9%) 3.484 ops/ms [Average]
  (min, avg, max) = (5.746, 5.963, 6.109), stdev = 0.191
  CI (99.9%): [2.479, 9.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.669 ops/ms
# Warmup Iteration   2: 5.329 ops/ms
# Warmup Iteration   3: 6.319 ops/ms
Iteration   1: 6.350 ops/ms
Iteration   2: 6.441 ops/ms
Iteration   3: 6.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.402 ±(99.9%) 0.862 ops/ms [Average]
  (min, avg, max) = (6.350, 6.402, 6.441), stdev = 0.047
  CI (99.9%): [5.540, 7.265] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 4.472 ops/ms
# Warmup Iteration   3: 5.923 ops/ms
Iteration   1: 5.887 ops/ms
Iteration   2: 5.652 ops/ms
Iteration   3: 6.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.880 ±(99.9%) 4.097 ops/ms [Average]
  (min, avg, max) = (5.652, 5.880, 6.101), stdev = 0.225
  CI (99.9%): [1.783, 9.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.347 ops/ms
# Warmup Iteration   3: 4.931 ops/ms
Iteration   1: 5.172 ops/ms
Iteration   2: 5.256 ops/ms
Iteration   3: 5.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.251 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (5.172, 5.251, 5.327), stdev = 0.077
  CI (99.9%): [3.840, 6.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 18.008 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.499 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.487 ±(99.9%) 0.012 ms/op
Iteration   1: 5.315 ±(99.9%) 0.016 ms/op
Iteration   2: 5.433 ±(99.9%) 0.018 ms/op
Iteration   3: 5.250 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.333 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (5.250, 5.333, 5.433), stdev = 0.093
  CI (99.9%): [3.634, 7.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.429 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.813 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.010 ms/op
Iteration   1: 5.004 ±(99.9%) 0.014 ms/op
Iteration   2: 4.925 ±(99.9%) 0.007 ms/op
Iteration   3: 5.129 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.019 ±(99.9%) 1.877 ms/op [Average]
  (min, avg, max) = (4.925, 5.019, 5.129), stdev = 0.103
  CI (99.9%): [3.142, 6.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.407 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.572 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.545 ±(99.9%) 0.008 ms/op
Iteration   1: 5.448 ±(99.9%) 0.009 ms/op
Iteration   2: 5.390 ±(99.9%) 0.011 ms/op
Iteration   3: 5.486 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.441 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (5.390, 5.441, 5.486), stdev = 0.048
  CI (99.9%): [4.560, 6.323] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.847 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 7.441 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.147 ±(99.9%) 0.015 ms/op
Iteration   1: 5.988 ±(99.9%) 0.014 ms/op
Iteration   2: 6.114 ±(99.9%) 0.013 ms/op
Iteration   3: 5.970 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.024 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (5.970, 6.024, 6.114), stdev = 0.078
  CI (99.9%): [4.592, 7.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.378 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.776 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.928 ±(99.9%) 0.028 ms/op
Iteration   1: 5.253 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.544 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  23.267 ms/op
                 createUser·p0.9999: 28.794 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   2: 5.371 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   7.876 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  24.113 ms/op
                 createUser·p0.9999: 30.904 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 5.491 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.265 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.545 ms/op
                 createUser·p0.99:   11.321 ms/op
                 createUser·p0.999:  29.057 ms/op
                 createUser·p0.9999: 31.579 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178777
  mean =      5.370 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 89660 
    [ 5.000,  7.500) = 79161 
    [ 7.500, 10.000) = 7689 
    [10.000, 12.500) = 1418 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     23.844 ms/op
     p(99.9900) =     31.236 ms/op
     p(99.9990) =     33.699 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.893 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.237 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.137 ±(99.9%) 0.018 ms/op
Iteration   1: 5.222 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.376 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.717 ms/op
                 existUser·p0.99:   11.059 ms/op
                 existUser·p0.999:  22.969 ms/op
                 existUser·p0.9999: 40.280 ms/op
                 existUser·p1.00:   41.288 ms/op

Iteration   2: 5.039 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.832 ms/op
                 existUser·p0.99:   9.548 ms/op
                 existUser·p0.999:  14.133 ms/op
                 existUser·p0.9999: 27.273 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 5.153 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.487 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  25.700 ms/op
                 existUser·p0.9999: 33.384 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186739
  mean =      5.137 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 114103 
    [ 5.000, 10.000) = 70314 
    [10.000, 15.000) = 2064 
    [15.000, 20.000) = 98 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 59 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     38.425 ms/op
     p(99.9990) =     41.003 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.550 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 6.173 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.738 ±(99.9%) 0.023 ms/op
Iteration   1: 5.187 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.406 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  22.598 ms/op
                 getUser·p0.9999: 25.980 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 5.416 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.613 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   9.835 ms/op
                 getUser·p0.999:  25.660 ms/op
                 getUser·p0.9999: 29.724 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   3: 5.421 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.815 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.693 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  25.691 ms/op
                 getUser·p0.9999: 29.101 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179620
  mean =      5.339 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 85945 
    [ 5.000,  7.500) = 84935 
    [ 7.500, 10.000) = 6876 
    [10.000, 12.500) = 1251 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     24.228 ms/op
     p(99.9900) =     29.035 ms/op
     p(99.9990) =     30.219 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.912 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 7.099 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.032 ±(99.9%) 0.024 ms/op
Iteration   1: 6.453 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  28.115 ms/op
                 listUser·p0.9999: 31.031 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   2: 6.064 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.218 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  28.674 ms/op
                 listUser·p0.9999: 33.777 ms/op
                 listUser·p1.00:   35.848 ms/op

Iteration   3: 6.353 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  24.139 ms/op
                 listUser·p0.9999: 26.475 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152675
  mean =      6.286 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 9878 
    [ 5.000,  7.500) = 126090 
    [ 7.500, 10.000) = 13051 
    [10.000, 12.500) = 2418 
    [12.500, 15.000) = 642 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      5.956 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     32.062 ms/op
     p(99.9990) =     35.676 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.963 ± 3.484  ops/ms
ClientPb.existUser                       thrpt       3   6.402 ± 0.862  ops/ms
ClientPb.getUser                         thrpt       3   5.880 ± 4.097  ops/ms
ClientPb.listUser                        thrpt       3   5.251 ± 1.411  ops/ms
ClientPb.createUser                       avgt       3   5.333 ± 1.699   ms/op
ClientPb.existUser                        avgt       3   5.019 ± 1.877   ms/op
ClientPb.getUser                          avgt       3   5.441 ± 0.882   ms/op
ClientPb.listUser                         avgt       3   6.024 ± 1.432   ms/op
ClientPb.createUser                     sample  178777   5.370 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.325           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.844           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  186739   5.137 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.316           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.356           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.089           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.425           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.288           ms/op
ClientPb.getUser                        sample  179620   5.339 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.745           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.496           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.093           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.228           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.035           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  152675   6.286 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.532           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.919           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.062           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.848           ms/op
