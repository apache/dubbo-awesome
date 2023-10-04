# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 5.708 ops/ms
# Warmup Iteration   3: 8.195 ops/ms
Iteration   1: 8.784 ops/ms
Iteration   2: 9.035 ops/ms
Iteration   3: 8.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.871 ±(99.9%) 2.599 ops/ms [Average]
  (min, avg, max) = (8.784, 8.871, 9.035), stdev = 0.142
  CI (99.9%): [6.272, 11.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.799 ops/ms
# Warmup Iteration   2: 8.396 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 9.468 ops/ms
Iteration   2: 9.488 ops/ms
Iteration   3: 9.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.449 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (9.391, 9.449, 9.488), stdev = 0.051
  CI (99.9%): [8.511, 10.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 8.497 ops/ms
# Warmup Iteration   3: 8.885 ops/ms
Iteration   1: 9.157 ops/ms
Iteration   2: 9.213 ops/ms
Iteration   3: 9.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.173 ±(99.9%) 0.633 ops/ms [Average]
  (min, avg, max) = (9.149, 9.173, 9.213), stdev = 0.035
  CI (99.9%): [8.540, 9.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 7.082 ops/ms
# Warmup Iteration   3: 7.361 ops/ms
Iteration   1: 7.541 ops/ms
Iteration   2: 7.491 ops/ms
Iteration   3: 7.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.557 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (7.491, 7.557, 7.639), stdev = 0.075
  CI (99.9%): [6.183, 8.931] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.193 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.006 ms/op
Iteration   1: 3.606 ±(99.9%) 0.007 ms/op
Iteration   2: 3.467 ±(99.9%) 0.008 ms/op
Iteration   3: 3.561 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.545 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.467, 3.545, 3.606), stdev = 0.071
  CI (99.9%): [2.258, 4.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.646 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.004 ms/op
Iteration   1: 3.401 ±(99.9%) 0.005 ms/op
Iteration   2: 3.389 ±(99.9%) 0.005 ms/op
Iteration   3: 3.271 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.354 ±(99.9%) 1.312 ms/op [Average]
  (min, avg, max) = (3.271, 3.354, 3.401), stdev = 0.072
  CI (99.9%): [2.042, 4.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.914 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.004 ms/op
Iteration   1: 3.589 ±(99.9%) 0.004 ms/op
Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
Iteration   3: 3.533 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.555 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (3.533, 3.555, 3.589), stdev = 0.030
  CI (99.9%): [3.006, 4.104] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.011 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.293 ±(99.9%) 0.005 ms/op
Iteration   1: 4.281 ±(99.9%) 0.008 ms/op
Iteration   2: 4.199 ±(99.9%) 0.006 ms/op
Iteration   3: 4.116 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.198 ±(99.9%) 1.508 ms/op [Average]
  (min, avg, max) = (4.116, 4.198, 4.281), stdev = 0.083
  CI (99.9%): [2.691, 5.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.273 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.010 ms/op
Iteration   1: 3.707 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  13.599 ms/op
                 createUser·p0.9999: 30.433 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   2: 3.597 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  23.724 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.561 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  19.910 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264944
  mean =      3.620 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4884 
    [ 2.500,  5.000) = 248185 
    [ 5.000,  7.500) = 9370 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     29.082 ms/op
     p(99.9990) =     30.748 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.514 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 18.809 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 3.342 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  17.825 ms/op
                 existUser·p0.9999: 20.082 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 3.439 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   7.445 ms/op
                 existUser·p0.999:  22.479 ms/op
                 existUser·p0.9999: 31.883 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282345
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8021 
    [ 2.500,  5.000) = 265392 
    [ 5.000,  7.500) = 7366 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     30.549 ms/op
     p(99.9990) =     32.722 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.869 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.011 ms/op
Iteration   1: 3.516 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  22.381 ms/op
                 getUser·p0.9999: 26.075 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 3.544 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  18.862 ms/op
                 getUser·p0.9999: 26.081 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272469
  mean =      3.520 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3985 
    [ 2.500,  5.000) = 258001 
    [ 5.000,  7.500) = 8526 
    [ 7.500, 10.000) = 1285 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     19.910 ms/op
     p(99.9900) =     25.502 ms/op
     p(99.9990) =     26.722 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.203 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.012 ms/op
Iteration   1: 4.337 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   4.157 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 4.223 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  16.472 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 4.177 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.791 ms/op
                 listUser·p0.9999: 23.866 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225975
  mean =      4.245 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 213518 
    [ 5.000,  7.500) = 8533 
    [ 7.500, 10.000) = 2743 
    [10.000, 12.500) = 446 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     16.942 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.264 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.871 ± 2.599  ops/ms
ClientPb.existUser                       thrpt       3   9.449 ± 0.938  ops/ms
ClientPb.getUser                         thrpt       3   9.173 ± 0.633  ops/ms
ClientPb.listUser                        thrpt       3   7.557 ± 1.374  ops/ms
ClientPb.createUser                       avgt       3   3.545 ± 1.287   ms/op
ClientPb.existUser                        avgt       3   3.354 ± 1.312   ms/op
ClientPb.getUser                          avgt       3   3.555 ± 0.549   ms/op
ClientPb.listUser                         avgt       3   4.198 ± 1.508   ms/op
ClientPb.createUser                     sample  264944   3.620 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.438           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.082           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.802           ms/op
ClientPb.existUser                      sample  282345   3.399 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.549           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.260           ms/op
ClientPb.getUser                        sample  272469   3.520 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.669           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.910           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.502           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  225975   4.245 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
