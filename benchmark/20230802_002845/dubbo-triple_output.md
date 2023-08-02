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
# Warmup Iteration   1: 1.870 ops/ms
# Warmup Iteration   2: 5.490 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 8.834 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 9.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.951 ±(99.9%) 3.224 ops/ms [Average]
  (min, avg, max) = (8.834, 8.951, 9.154), stdev = 0.177
  CI (99.9%): [5.727, 12.174] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.065 ops/ms
# Warmup Iteration   2: 8.240 ops/ms
# Warmup Iteration   3: 8.820 ops/ms
Iteration   1: 9.159 ops/ms
Iteration   2: 9.308 ops/ms
Iteration   3: 9.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.270 ±(99.9%) 1.789 ops/ms [Average]
  (min, avg, max) = (9.159, 9.270, 9.344), stdev = 0.098
  CI (99.9%): [7.481, 11.059] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.573 ops/ms
# Warmup Iteration   2: 8.101 ops/ms
# Warmup Iteration   3: 8.722 ops/ms
Iteration   1: 9.152 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.327 ±(99.9%) 3.120 ops/ms [Average]
  (min, avg, max) = (9.152, 9.327, 9.494), stdev = 0.171
  CI (99.9%): [6.207, 12.447] (assumes normal distribution)


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
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 6.552 ops/ms
# Warmup Iteration   3: 7.540 ops/ms
Iteration   1: 7.804 ops/ms
Iteration   2: 7.694 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.776 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (7.694, 7.776, 7.831), stdev = 0.072
  CI (99.9%): [6.454, 9.098] (assumes normal distribution)


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
# Warmup Iteration   1: 9.368 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.005 ms/op
Iteration   1: 3.467 ±(99.9%) 0.006 ms/op
Iteration   2: 3.519 ±(99.9%) 0.009 ms/op
Iteration   3: 3.555 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.514 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.467, 3.514, 3.555), stdev = 0.044
  CI (99.9%): [2.705, 4.323] (assumes normal distribution)


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
# Warmup Iteration   1: 9.385 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.002 ms/op
Iteration   1: 3.341 ±(99.9%) 0.005 ms/op
Iteration   2: 3.322 ±(99.9%) 0.009 ms/op
Iteration   3: 3.281 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.315 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.281, 3.315, 3.341), stdev = 0.031
  CI (99.9%): [2.754, 3.875] (assumes normal distribution)


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
# Warmup Iteration   1: 9.951 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.005 ms/op
Iteration   1: 3.542 ±(99.9%) 0.006 ms/op
Iteration   2: 3.444 ±(99.9%) 0.004 ms/op
Iteration   3: 3.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.494 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.444, 3.494, 3.542), stdev = 0.050
  CI (99.9%): [2.591, 4.398] (assumes normal distribution)


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
# Warmup Iteration   1: 10.686 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.009 ms/op
Iteration   1: 4.073 ±(99.9%) 0.008 ms/op
Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
Iteration   3: 4.046 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.049 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (4.029, 4.049, 4.073), stdev = 0.023
  CI (99.9%): [3.636, 4.462] (assumes normal distribution)


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
# Warmup Iteration   1: 9.245 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.010 ms/op
Iteration   1: 3.549 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  21.651 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 3.481 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  22.420 ms/op
                 createUser·p0.9999: 27.492 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.049 ms/op
                 createUser·p0.999:  21.153 ms/op
                 createUser·p0.9999: 28.508 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275348
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4102 
    [ 2.500,  5.000) = 264225 
    [ 5.000,  7.500) = 5416 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.468 ms/op
     p(99.9000) =     21.529 ms/op
     p(99.9900) =     27.654 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 8.578 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  19.628 ms/op
                 existUser·p0.9999: 23.126 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  21.933 ms/op
                 existUser·p0.9999: 25.793 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.725 ms/op
                 existUser·p0.999:  18.535 ms/op
                 existUser·p0.9999: 28.393 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279850
  mean =      3.429 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3849 
    [ 2.500,  5.000) = 267347 
    [ 5.000,  7.500) = 7094 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     19.226 ms/op
     p(99.9900) =     27.003 ms/op
     p(99.9990) =     29.210 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.907 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  12.900 ms/op
                 getUser·p0.9999: 26.600 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.446 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  19.497 ms/op
                 getUser·p0.9999: 23.608 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.552 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  19.656 ms/op
                 getUser·p0.9999: 34.603 ms/op
                 getUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275035
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5288 
    [ 2.500,  5.000) = 261307 
    [ 5.000,  7.500) = 6984 
    [ 7.500, 10.000) = 1066 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     15.169 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 10.691 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.014 ms/op
Iteration   1: 4.190 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  22.872 ms/op
                 listUser·p0.9999: 25.559 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 4.210 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 18.639 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  14.087 ms/op
                 listUser·p0.9999: 16.792 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230503
  mean =      4.162 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 220013 
    [ 5.000,  7.500) = 7537 
    [ 7.500, 10.000) = 1965 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     16.359 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.951 ± 3.224  ops/ms
ClientPb.existUser                       thrpt       3   9.270 ± 1.789  ops/ms
ClientPb.getUser                         thrpt       3   9.327 ± 3.120  ops/ms
ClientPb.listUser                        thrpt       3   7.776 ± 1.322  ops/ms
ClientPb.createUser                       avgt       3   3.514 ± 0.809   ms/op
ClientPb.existUser                        avgt       3   3.315 ± 0.561   ms/op
ClientPb.getUser                          avgt       3   3.494 ± 0.904   ms/op
ClientPb.listUser                         avgt       3   4.049 ± 0.413   ms/op
ClientPb.createUser                     sample  275348   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.638           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.468           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.529           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.654           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  279850   3.429 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.824           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.226           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.003           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  275035   3.488 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.509           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.169           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.554           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  230503   4.162 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.359           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
