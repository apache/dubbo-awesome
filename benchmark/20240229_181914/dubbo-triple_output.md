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
# Warmup Iteration   1: 5.358 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.600 ops/ms
Iteration   1: 12.826 ops/ms
Iteration   2: 12.573 ops/ms
Iteration   3: 12.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.729 ±(99.9%) 2.494 ops/ms [Average]
  (min, avg, max) = (12.573, 12.729, 12.826), stdev = 0.137
  CI (99.9%): [10.236, 15.223] (assumes normal distribution)


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
# Warmup Iteration   1: 8.422 ops/ms
# Warmup Iteration   2: 13.621 ops/ms
# Warmup Iteration   3: 13.501 ops/ms
Iteration   1: 13.441 ops/ms
Iteration   2: 13.427 ops/ms
Iteration   3: 13.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.451 ±(99.9%) 0.546 ops/ms [Average]
  (min, avg, max) = (13.427, 13.451, 13.484), stdev = 0.030
  CI (99.9%): [12.904, 13.997] (assumes normal distribution)


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
# Warmup Iteration   1: 7.986 ops/ms
# Warmup Iteration   2: 13.018 ops/ms
# Warmup Iteration   3: 12.944 ops/ms
Iteration   1: 12.997 ops/ms
Iteration   2: 13.042 ops/ms
Iteration   3: 13.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.091 ±(99.9%) 2.296 ops/ms [Average]
  (min, avg, max) = (12.997, 13.091, 13.234), stdev = 0.126
  CI (99.9%): [10.796, 15.387] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.043 ops/ms
# Warmup Iteration   2: 10.775 ops/ms
# Warmup Iteration   3: 10.824 ops/ms
Iteration   1: 10.945 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.898 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (10.829, 10.898, 10.945), stdev = 0.061
  CI (99.9%): [9.783, 12.014] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.003 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.470 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.461, 2.470, 2.485), stdev = 0.013
  CI (99.9%): [2.242, 2.699] (assumes normal distribution)


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.003 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.406 ±(99.9%) 0.004 ms/op
Iteration   3: 2.413 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.409 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.406, 2.409, 2.413), stdev = 0.004
  CI (99.9%): [2.339, 2.480] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.427 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.417, 2.427, 2.439), stdev = 0.011
  CI (99.9%): [2.223, 2.631] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.547 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
Iteration   1: 2.942 ±(99.9%) 0.005 ms/op
Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
Iteration   3: 2.949 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.942, 2.951, 2.962), stdev = 0.010
  CI (99.9%): [2.767, 3.135] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  6.065 ms/op
                 createUser·p0.9999: 15.009 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  9.381 ms/op
                 createUser·p0.9999: 11.767 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  8.221 ms/op
                 createUser·p0.9999: 10.306 ms/op
                 createUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385095
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 186344 
    [ 2.500,  3.750) = 194349 
    [ 3.750,  5.000) = 3531 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.217 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
Iteration   1: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  5.237 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.962 ms/op
                 existUser·p0.9999: 13.462 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  7.259 ms/op
                 existUser·p0.9999: 12.091 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398855
  mean =      2.404 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 203299 
    [ 2.500,  3.750) = 192092 
    [ 3.750,  5.000) = 2364 
    [ 5.000,  6.250) = 646 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      6.218 ms/op
     p(99.9900) =     13.306 ms/op
     p(99.9990) =     13.993 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  6.529 ms/op
                 getUser·p0.9999: 13.845 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  9.999 ms/op
                 getUser·p0.9999: 14.696 ms/op
                 getUser·p1.00:   16.253 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  8.387 ms/op
                 getUser·p0.9999: 12.124 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385439
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 191946 
    [ 2.500,  3.750) = 187372 
    [ 3.750,  5.000) = 5104 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      8.554 ms/op
     p(99.9900) =     14.278 ms/op
     p(99.9990) =     15.462 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.792 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.344 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.933 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.517 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.650 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316420
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 88228 
    [ 2.500,  3.750) = 187246 
    [ 3.750,  5.000) = 32639 
    [ 5.000,  6.250) = 6555 
    [ 6.250,  7.500) = 913 
    [ 7.500,  8.750) = 207 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     10.994 ms/op
     p(99.9990) =     12.089 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.729 ± 2.494  ops/ms
ClientPb.existUser                       thrpt       3  13.451 ± 0.546  ops/ms
ClientPb.getUser                         thrpt       3  13.091 ± 2.296  ops/ms
ClientPb.listUser                        thrpt       3  10.898 ± 1.116  ops/ms
ClientPb.createUser                       avgt       3   2.470 ± 0.229   ms/op
ClientPb.existUser                        avgt       3   2.409 ± 0.071   ms/op
ClientPb.getUser                          avgt       3   2.427 ± 0.204   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.184   ms/op
ClientPb.createUser                     sample  385095   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.787           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.217           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.188           ms/op
ClientPb.existUser                      sample  398855   2.404 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.695           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.218           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.306           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.941           ms/op
ClientPb.getUser                        sample  385439   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.662           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.554           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.253           ms/op
ClientPb.listUser                       sample  316420   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.814           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
