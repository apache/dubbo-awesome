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
# Warmup Iteration   1: 1.179 ops/ms
# Warmup Iteration   2: 2.919 ops/ms
# Warmup Iteration   3: 6.151 ops/ms
Iteration   1: 5.984 ops/ms
Iteration   2: 6.197 ops/ms
Iteration   3: 6.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.145 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (5.984, 6.145, 6.253), stdev = 0.142
  CI (99.9%): [3.563, 8.726] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.861 ops/ms
# Warmup Iteration   2: 5.419 ops/ms
# Warmup Iteration   3: 6.248 ops/ms
Iteration   1: 6.634 ops/ms
Iteration   2: 6.693 ops/ms
Iteration   3: 6.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.566 ±(99.9%) 3.127 ops/ms [Average]
  (min, avg, max) = (6.371, 6.566, 6.693), stdev = 0.171
  CI (99.9%): [3.440, 9.693] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.669 ops/ms
# Warmup Iteration   2: 4.572 ops/ms
# Warmup Iteration   3: 6.031 ops/ms
Iteration   1: 6.042 ops/ms
Iteration   2: 6.167 ops/ms
Iteration   3: 6.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.186 ±(99.9%) 2.826 ops/ms [Average]
  (min, avg, max) = (6.042, 6.186, 6.350), stdev = 0.155
  CI (99.9%): [3.361, 9.012] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.631 ops/ms
# Warmup Iteration   2: 4.408 ops/ms
# Warmup Iteration   3: 5.225 ops/ms
Iteration   1: 5.146 ops/ms
Iteration   2: 5.444 ops/ms
Iteration   3: 5.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.310 ±(99.9%) 2.764 ops/ms [Average]
  (min, avg, max) = (5.146, 5.310, 5.444), stdev = 0.151
  CI (99.9%): [2.547, 8.074] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 15.530 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.978 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.372 ±(99.9%) 0.009 ms/op
Iteration   1: 4.911 ±(99.9%) 0.022 ms/op
Iteration   2: 4.858 ±(99.9%) 0.019 ms/op
Iteration   3: 5.019 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.929 ±(99.9%) 1.496 ms/op [Average]
  (min, avg, max) = (4.858, 4.929, 5.019), stdev = 0.082
  CI (99.9%): [3.433, 6.425] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.283 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.408 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.959 ±(99.9%) 0.004 ms/op
Iteration   1: 4.941 ±(99.9%) 0.007 ms/op
Iteration   2: 4.742 ±(99.9%) 0.016 ms/op
Iteration   3: 4.963 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.882 ±(99.9%) 2.219 ms/op [Average]
  (min, avg, max) = (4.742, 4.882, 4.963), stdev = 0.122
  CI (99.9%): [2.664, 7.101] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.174 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.989 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.295 ±(99.9%) 0.007 ms/op
Iteration   1: 5.290 ±(99.9%) 0.012 ms/op
Iteration   2: 5.178 ±(99.9%) 0.009 ms/op
Iteration   3: 5.091 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.186 ±(99.9%) 1.826 ms/op [Average]
  (min, avg, max) = (5.091, 5.186, 5.290), stdev = 0.100
  CI (99.9%): [3.360, 7.012] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.093 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.808 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.260 ±(99.9%) 0.012 ms/op
Iteration   1: 5.988 ±(99.9%) 0.017 ms/op
Iteration   2: 6.112 ±(99.9%) 0.018 ms/op
Iteration   3: 5.887 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.995 ±(99.9%) 2.056 ms/op [Average]
  (min, avg, max) = (5.887, 5.995, 6.112), stdev = 0.113
  CI (99.9%): [3.939, 8.052] (assumes normal distribution)


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
# Warmup Iteration   1: 16.440 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.569 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.561 ±(99.9%) 0.024 ms/op
Iteration   1: 5.195 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.160 ms/op
                 createUser·p0.99:   9.191 ms/op
                 createUser·p0.999:  21.708 ms/op
                 createUser·p0.9999: 26.570 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 5.085 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  24.718 ms/op
                 createUser·p0.9999: 26.851 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 5.188 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   6.808 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  25.135 ms/op
                 createUser·p0.9999: 28.798 ms/op
                 createUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 186050
  mean =      5.155 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 98481 
    [ 5.000,  7.500) = 81777 
    [ 7.500, 10.000) = 4578 
    [10.000, 12.500) = 742 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      6.898 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     21.953 ms/op
     p(99.9900) =     28.226 ms/op
     p(99.9990) =     29.798 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 14.663 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.869 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.107 ±(99.9%) 0.016 ms/op
Iteration   1: 4.849 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.066 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   8.315 ms/op
                 existUser·p0.999:  15.319 ms/op
                 existUser·p0.9999: 28.521 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   2: 4.884 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   5.636 ms/op
                 existUser·p0.95:   6.300 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  16.347 ms/op
                 existUser·p0.9999: 29.342 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 4.790 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  20.560 ms/op
                 existUser·p0.9999: 29.086 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 198265
  mean =      4.841 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 145560 
    [ 5.000,  7.500) = 48305 
    [ 7.500, 10.000) = 3376 
    [10.000, 12.500) = 599 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.066 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.338 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.912 ms/op
     p(99.9900) =     28.826 ms/op
     p(99.9990) =     29.953 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.892 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.037 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.276 ±(99.9%) 0.018 ms/op
Iteration   1: 5.295 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  22.124 ms/op
                 getUser·p0.9999: 26.770 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   2: 5.273 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.572 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.111 ms/op
                 getUser·p0.99:   9.208 ms/op
                 getUser·p0.999:  26.194 ms/op
                 getUser·p0.9999: 29.206 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   3: 5.214 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.732 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   7.021 ms/op
                 getUser·p0.99:   9.814 ms/op
                 getUser·p0.999:  25.379 ms/op
                 getUser·p0.9999: 36.167 ms/op
                 getUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182426
  mean =      5.260 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 93409 
    [ 5.000,  7.500) = 80675 
    [ 7.500, 10.000) = 6297 
    [10.000, 12.500) = 1336 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     22.647 ms/op
     p(99.9900) =     33.350 ms/op
     p(99.9990) =     37.575 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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
# Warmup Iteration   1: 17.410 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.515 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.046 ±(99.9%) 0.020 ms/op
Iteration   1: 6.254 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  26.411 ms/op
                 listUser·p0.9999: 28.996 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   2: 6.069 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.961 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  26.870 ms/op
                 listUser·p0.9999: 30.245 ms/op
                 listUser·p1.00:   30.704 ms/op

Iteration   3: 5.946 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   8.192 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  21.470 ms/op
                 listUser·p0.9999: 26.054 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157634
  mean =      6.087 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 9659 
    [ 5.000,  7.500) = 137334 
    [ 7.500, 10.000) = 7657 
    [10.000, 12.500) = 2171 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.359 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     25.211 ms/op
     p(99.9900) =     29.457 ms/op
     p(99.9990) =     30.628 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.145 ± 2.582  ops/ms
ClientPb.existUser                       thrpt       3   6.566 ± 3.127  ops/ms
ClientPb.getUser                         thrpt       3   6.186 ± 2.826  ops/ms
ClientPb.listUser                        thrpt       3   5.310 ± 2.764  ops/ms
ClientPb.createUser                       avgt       3   4.929 ± 1.496   ms/op
ClientPb.existUser                        avgt       3   4.882 ± 2.219   ms/op
ClientPb.getUser                          avgt       3   5.186 ± 1.826   ms/op
ClientPb.listUser                         avgt       3   5.995 ± 2.056   ms/op
ClientPb.createUser                     sample  186050   5.155 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.708           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.201           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.110           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.953           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.226           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  198265   4.841 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.066           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.338           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.651           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.826           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.114           ms/op
ClientPb.getUser                        sample  182426   5.260 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.372           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.981           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.207           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.647           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.350           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.683           ms/op
ClientPb.listUser                       sample  157634   6.087 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.359           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.036           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.928           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.211           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.457           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.704           ms/op
