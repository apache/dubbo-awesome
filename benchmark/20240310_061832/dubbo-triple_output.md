# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.680 ops/ms
# Warmup Iteration   2: 12.024 ops/ms
# Warmup Iteration   3: 12.455 ops/ms
Iteration   1: 12.834 ops/ms
Iteration   2: 12.826 ops/ms
Iteration   3: 12.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.869 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (12.826, 12.869, 12.945), stdev = 0.067
  CI (99.9%): [11.653, 14.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.384 ops/ms
# Warmup Iteration   2: 13.578 ops/ms
# Warmup Iteration   3: 13.472 ops/ms
Iteration   1: 13.491 ops/ms
Iteration   2: 13.495 ops/ms
Iteration   3: 13.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.467 ±(99.9%) 0.831 ops/ms [Average]
  (min, avg, max) = (13.414, 13.467, 13.495), stdev = 0.046
  CI (99.9%): [12.636, 14.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.974 ops/ms
# Warmup Iteration   2: 12.765 ops/ms
# Warmup Iteration   3: 12.849 ops/ms
Iteration   1: 12.910 ops/ms
Iteration   2: 13.019 ops/ms
Iteration   3: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.946 ±(99.9%) 1.158 ops/ms [Average]
  (min, avg, max) = (12.908, 12.946, 13.019), stdev = 0.063
  CI (99.9%): [11.787, 14.104] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.991 ops/ms
# Warmup Iteration   2: 10.591 ops/ms
# Warmup Iteration   3: 10.767 ops/ms
Iteration   1: 10.823 ops/ms
Iteration   2: 10.779 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.779 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (10.736, 10.779, 10.823), stdev = 0.043
  CI (99.9%): [9.986, 11.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.485, 2.507, 2.517), stdev = 0.018
  CI (99.9%): [2.174, 2.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.584 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.392 ±(99.9%) 0.004 ms/op
Iteration   1: 2.400 ±(99.9%) 0.004 ms/op
Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
Iteration   3: 2.396 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.398 ±(99.9%) 0.042 ms/op [Average]
  (min, avg, max) = (2.396, 2.398, 2.400), stdev = 0.002
  CI (99.9%): [2.356, 2.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.003 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.423 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.406, 2.423, 2.443), stdev = 0.018
  CI (99.9%): [2.087, 2.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.695 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
Iteration   3: 2.998 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.998, 3.008, 3.028), stdev = 0.017
  CI (99.9%): [2.695, 3.322] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  10.058 ms/op
                 createUser·p0.9999: 13.225 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  8.069 ms/op
                 createUser·p0.9999: 12.782 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.758 ms/op
                 createUser·p0.9999: 10.243 ms/op
                 createUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385245
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189398 
    [ 2.500,  3.750) = 192291 
    [ 3.750,  5.000) = 2717 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.745 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.477 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  5.965 ms/op
                 existUser·p0.9999: 14.038 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  6.200 ms/op
                 existUser·p0.9999: 17.303 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 10.747 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392149
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 195315 
    [ 2.500,  3.750) = 194219 
    [ 3.750,  5.000) = 1962 
    [ 5.000,  6.250) = 217 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      6.662 ms/op
     p(99.9900) =     14.651 ms/op
     p(99.9990) =     17.740 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  11.596 ms/op
                 getUser·p0.9999: 13.390 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  9.248 ms/op
                 getUser·p0.9999: 11.687 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  7.568 ms/op
                 getUser·p0.9999: 10.334 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384540
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 191328 
    [ 2.500,  3.750) = 186901 
    [ 3.750,  5.000) = 4778 
    [ 5.000,  6.250) = 853 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      8.133 ms/op
     p(99.9900) =     12.969 ms/op
     p(99.9990) =     13.585 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.009 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.925 ms/op
                 listUser·p0.9999: 10.492 ms/op
                 listUser·p1.00:   10.977 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.187 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 12.162 ms/op
                 listUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319954
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 92639 
    [ 2.500,  3.750) = 188587 
    [ 3.750,  5.000) = 31843 
    [ 5.000,  6.250) = 5573 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     13.602 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.869 ± 1.216  ops/ms
ClientPb.existUser                       thrpt       3  13.467 ± 0.831  ops/ms
ClientPb.getUser                         thrpt       3  12.946 ± 1.158  ops/ms
ClientPb.listUser                        thrpt       3  10.779 ± 0.793  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.333   ms/op
ClientPb.existUser                        avgt       3   2.398 ± 0.042   ms/op
ClientPb.getUser                          avgt       3   2.423 ± 0.336   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.314   ms/op
ClientPb.createUser                     sample  385245   2.489 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.745           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.009           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.417           ms/op
ClientPb.existUser                      sample  392149   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.840           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.662           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.651           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.153           ms/op
ClientPb.getUser                        sample  384540   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.586           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.133           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.969           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.828           ms/op
ClientPb.listUser                       sample  319954   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.877           ms/op
