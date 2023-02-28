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
# Warmup Iteration   1: 2.056 ops/ms
# Warmup Iteration   2: 5.761 ops/ms
# Warmup Iteration   3: 8.647 ops/ms
Iteration   1: 9.284 ops/ms
Iteration   2: 9.226 ops/ms
Iteration   3: 9.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.251 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (9.226, 9.251, 9.284), stdev = 0.030
  CI (99.9%): [8.710, 9.792] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 9.374 ops/ms
Iteration   1: 9.713 ops/ms
Iteration   2: 9.768 ops/ms
Iteration   3: 9.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.671 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (9.533, 9.671, 9.768), stdev = 0.123
  CI (99.9%): [7.433, 11.910] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.758 ops/ms
# Warmup Iteration   2: 8.433 ops/ms
# Warmup Iteration   3: 8.929 ops/ms
Iteration   1: 9.478 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.395 ±(99.9%) 3.358 ops/ms [Average]
  (min, avg, max) = (9.184, 9.395, 9.523), stdev = 0.184
  CI (99.9%): [6.037, 12.752] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.609 ops/ms
# Warmup Iteration   2: 6.936 ops/ms
# Warmup Iteration   3: 7.834 ops/ms
Iteration   1: 8.055 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.085 ±(99.9%) 2.797 ops/ms [Average]
  (min, avg, max) = (7.949, 8.085, 8.251), stdev = 0.153
  CI (99.9%): [5.288, 10.882] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.214 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.006 ms/op
Iteration   1: 3.505 ±(99.9%) 0.005 ms/op
Iteration   2: 3.366 ±(99.9%) 0.011 ms/op
Iteration   3: 3.423 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.431 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.366, 3.431, 3.505), stdev = 0.070
  CI (99.9%): [2.154, 4.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.038 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.003 ms/op
Iteration   1: 3.346 ±(99.9%) 0.010 ms/op
Iteration   2: 3.196 ±(99.9%) 0.009 ms/op
Iteration   3: 3.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.330 ±(99.9%) 2.304 ms/op [Average]
  (min, avg, max) = (3.196, 3.330, 3.447), stdev = 0.126
  CI (99.9%): [1.025, 5.634] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.009 ms/op
Iteration   1: 3.616 ±(99.9%) 0.008 ms/op
Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
Iteration   3: 3.491 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.489 ±(99.9%) 2.332 ms/op [Average]
  (min, avg, max) = (3.360, 3.489, 3.616), stdev = 0.128
  CI (99.9%): [1.157, 5.821] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.747 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.008 ms/op
Iteration   1: 3.917 ±(99.9%) 0.009 ms/op
Iteration   2: 3.875 ±(99.9%) 0.010 ms/op
Iteration   3: 4.036 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.943 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (3.875, 3.943, 4.036), stdev = 0.084
  CI (99.9%): [2.412, 5.473] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.194 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.012 ms/op
Iteration   1: 3.321 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   6.102 ms/op
                 createUser·p0.999:  16.417 ms/op
                 createUser·p0.9999: 21.540 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.465 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  20.243 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  21.548 ms/op
                 createUser·p0.9999: 26.958 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281833
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6697 
    [ 2.500,  5.000) = 268791 
    [ 5.000,  7.500) = 5048 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 194 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     20.191 ms/op
     p(99.9900) =     26.667 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.496 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.008 ms/op
Iteration   1: 3.372 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 22.808 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 3.408 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  21.463 ms/op
                 existUser·p0.9999: 25.121 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  19.307 ms/op
                 existUser·p0.9999: 28.559 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283459
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18289 
    [ 2.500,  5.000) = 258052 
    [ 5.000,  7.500) = 5959 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     15.206 ms/op
     p(99.9900) =     26.989 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.004 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.012 ms/op
Iteration   1: 3.619 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  23.209 ms/op
                 getUser·p0.9999: 27.176 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.966 ms/op
                 getUser·p0.9999: 29.538 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274558
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3118 
    [ 2.500,  5.000) = 261761 
    [ 5.000,  7.500) = 8237 
    [ 7.500, 10.000) = 866 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     21.346 ms/op
     p(99.9900) =     28.297 ms/op
     p(99.9990) =     30.214 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.398 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.013 ms/op
Iteration   1: 4.172 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  22.136 ms/op
                 listUser·p0.9999: 35.695 ms/op
                 listUser·p1.00:   37.421 ms/op

Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 18.218 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.123 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.682 ms/op
                 listUser·p0.999:  15.228 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234416
  mean =      4.094 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 224206 
    [ 5.000,  7.500) = 7627 
    [ 7.500, 10.000) = 1661 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     17.058 ms/op
     p(99.9900) =     28.191 ms/op
     p(99.9990) =     36.678 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.251 ± 0.541  ops/ms
ClientPb.existUser                       thrpt       3   9.671 ± 2.239  ops/ms
ClientPb.getUser                         thrpt       3   9.395 ± 3.358  ops/ms
ClientPb.listUser                        thrpt       3   8.085 ± 2.797  ops/ms
ClientPb.createUser                       avgt       3   3.431 ± 1.278   ms/op
ClientPb.existUser                        avgt       3   3.330 ± 2.304   ms/op
ClientPb.getUser                          avgt       3   3.489 ± 2.332   ms/op
ClientPb.listUser                         avgt       3   3.943 ± 1.531   ms/op
ClientPb.createUser                     sample  281833   3.406 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.191           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.667           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.623           ms/op
ClientPb.existUser                      sample  283459   3.384 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.425           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.206           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.989           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  274558   3.494 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.955           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.346           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.297           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  234416   4.094 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.268           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.058           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.191           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.421           ms/op
