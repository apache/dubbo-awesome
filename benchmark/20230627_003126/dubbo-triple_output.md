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
# Warmup Iteration   1: 0.954 ops/ms
# Warmup Iteration   2: 2.175 ops/ms
# Warmup Iteration   3: 4.660 ops/ms
Iteration   1: 5.081 ops/ms
Iteration   2: 5.397 ops/ms
Iteration   3: 5.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.295 ±(99.9%) 3.383 ops/ms [Average]
  (min, avg, max) = (5.081, 5.295, 5.407), stdev = 0.185
  CI (99.9%): [1.912, 8.678] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.346 ops/ms
# Warmup Iteration   2: 4.217 ops/ms
# Warmup Iteration   3: 5.714 ops/ms
Iteration   1: 5.785 ops/ms
Iteration   2: 5.850 ops/ms
Iteration   3: 5.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.876 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (5.785, 5.876, 5.993), stdev = 0.106
  CI (99.9%): [3.935, 7.817] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.249 ops/ms
# Warmup Iteration   2: 4.035 ops/ms
# Warmup Iteration   3: 5.432 ops/ms
Iteration   1: 5.350 ops/ms
Iteration   2: 5.374 ops/ms
Iteration   3: 5.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.407 ±(99.9%) 1.450 ops/ms [Average]
  (min, avg, max) = (5.350, 5.407, 5.498), stdev = 0.079
  CI (99.9%): [3.957, 6.857] (assumes normal distribution)


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
# Warmup Iteration   1: 1.414 ops/ms
# Warmup Iteration   2: 3.739 ops/ms
# Warmup Iteration   3: 4.631 ops/ms
Iteration   1: 4.680 ops/ms
Iteration   2: 4.840 ops/ms
Iteration   3: 4.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.734 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (4.680, 4.734, 4.840), stdev = 0.091
  CI (99.9%): [3.072, 6.397] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.838 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.666 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.273 ±(99.9%) 0.014 ms/op
Iteration   1: 5.618 ±(99.9%) 0.011 ms/op
Iteration   2: 5.516 ±(99.9%) 0.021 ms/op
Iteration   3: 5.756 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.630 ±(99.9%) 2.198 ms/op [Average]
  (min, avg, max) = (5.516, 5.630, 5.756), stdev = 0.120
  CI (99.9%): [3.432, 7.829] (assumes normal distribution)


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
# Warmup Iteration   1: 16.806 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.128 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.455 ±(99.9%) 0.015 ms/op
Iteration   1: 5.542 ±(99.9%) 0.014 ms/op
Iteration   2: 5.331 ±(99.9%) 0.012 ms/op
Iteration   3: 5.346 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.406 ±(99.9%) 2.155 ms/op [Average]
  (min, avg, max) = (5.331, 5.406, 5.542), stdev = 0.118
  CI (99.9%): [3.252, 7.561] (assumes normal distribution)


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
# Warmup Iteration   1: 18.334 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.756 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.531 ±(99.9%) 0.010 ms/op
Iteration   1: 5.588 ±(99.9%) 0.014 ms/op
Iteration   2: 5.608 ±(99.9%) 0.008 ms/op
Iteration   3: 5.676 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.624 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (5.588, 5.624, 5.676), stdev = 0.046
  CI (99.9%): [4.789, 6.459] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.060 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 7.529 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.538 ±(99.9%) 0.009 ms/op
Iteration   1: 6.628 ±(99.9%) 0.015 ms/op
Iteration   2: 6.699 ±(99.9%) 0.011 ms/op
Iteration   3: 6.549 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.626 ±(99.9%) 1.366 ms/op [Average]
  (min, avg, max) = (6.549, 6.626, 6.699), stdev = 0.075
  CI (99.9%): [5.260, 7.991] (assumes normal distribution)


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
# Warmup Iteration   1: 18.191 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.395 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.856 ±(99.9%) 0.022 ms/op
Iteration   1: 5.858 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.716 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.234 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   10.865 ms/op
                 createUser·p0.999:  15.226 ms/op
                 createUser·p0.9999: 28.689 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 5.625 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.470 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.971 ms/op
                 createUser·p0.99:   11.342 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 38.384 ms/op
                 createUser·p1.00:   41.419 ms/op

Iteration   3: 5.679 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.404 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   7.823 ms/op
                 createUser·p0.99:   10.910 ms/op
                 createUser·p0.999:  27.646 ms/op
                 createUser·p0.9999: 30.519 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167861
  mean =      5.719 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 42987 
    [ 5.000, 10.000) = 122236 
    [10.000, 15.000) = 2379 
    [15.000, 20.000) = 122 
    [20.000, 25.000) = 9 
    [25.000, 30.000) = 78 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.404 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     36.386 ms/op
     p(99.9990) =     41.374 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


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
# Warmup Iteration   1: 16.358 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 6.400 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.385 ±(99.9%) 0.018 ms/op
Iteration   1: 5.117 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.250 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 27.910 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   2: 5.196 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.480 ms/op
                 existUser·p0.95:   7.201 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  13.005 ms/op
                 existUser·p0.9999: 33.304 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   3: 5.304 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.602 ms/op
                 existUser·p0.99:   9.699 ms/op
                 existUser·p0.999:  27.874 ms/op
                 existUser·p0.9999: 32.211 ms/op
                 existUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184444
  mean =      5.205 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 96579 
    [ 5.000,  7.500) = 79987 
    [ 7.500, 10.000) = 6482 
    [10.000, 12.500) = 894 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     16.528 ms/op
     p(99.9900) =     32.211 ms/op
     p(99.9990) =     33.626 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 17.813 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.659 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.021 ms/op
Iteration   1: 5.467 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.335 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.574 ms/op
                 getUser·p0.95:   7.471 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  15.271 ms/op
                 getUser·p0.9999: 26.678 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 5.804 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.619 ms/op
                 getUser·p0.95:   9.060 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  25.672 ms/op
                 getUser·p0.9999: 34.365 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 5.423 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.568 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.491 ms/op
                 getUser·p0.95:   7.274 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  28.846 ms/op
                 getUser·p0.9999: 34.086 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172598
  mean =      5.560 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 61282 
    [ 5.000,  7.500) = 100047 
    [ 7.500, 10.000) = 8361 
    [10.000, 12.500) = 2055 
    [12.500, 15.000) = 438 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     33.734 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 18.638 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 8.176 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.618 ±(99.9%) 0.029 ms/op
Iteration   1: 6.343 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  30.188 ms/op
                 listUser·p0.9999: 35.652 ms/op
                 listUser·p1.00:   36.241 ms/op

Iteration   2: 6.402 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  30.687 ms/op
                 listUser·p0.9999: 34.734 ms/op
                 listUser·p1.00:   35.455 ms/op

Iteration   3: 6.627 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  25.936 ms/op
                 listUser·p0.9999: 32.714 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148779
  mean =      6.455 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 4294 
    [ 5.000,  7.500) = 128435 
    [ 7.500, 10.000) = 11735 
    [10.000, 12.500) = 2808 
    [12.500, 15.000) = 725 
    [15.000, 17.500) = 335 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 84 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.749 ms/op
     p(99.0000) =     12.501 ms/op
     p(99.9000) =     29.426 ms/op
     p(99.9900) =     35.266 ms/op
     p(99.9990) =     36.114 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.295 ± 3.383  ops/ms
ClientPb.existUser                       thrpt       3   5.876 ± 1.941  ops/ms
ClientPb.getUser                         thrpt       3   5.407 ± 1.450  ops/ms
ClientPb.listUser                        thrpt       3   4.734 ± 1.663  ops/ms
ClientPb.createUser                       avgt       3   5.630 ± 2.198   ms/op
ClientPb.existUser                        avgt       3   5.406 ± 2.155   ms/op
ClientPb.getUser                          avgt       3   5.624 ± 0.835   ms/op
ClientPb.listUser                         avgt       3   6.626 ± 1.366   ms/op
ClientPb.createUser                     sample  167861   5.719 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.404           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.971           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.957           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.419           ms/op
ClientPb.existUser                      sample  184444   5.205 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.299           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.486           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.528           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  172598   5.560 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.251           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.004           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.348           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.734           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  148779   6.455 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.446           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.501           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.266           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.241           ms/op
