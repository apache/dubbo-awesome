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
# Warmup Iteration   1: 1.832 ops/ms
# Warmup Iteration   2: 5.735 ops/ms
# Warmup Iteration   3: 8.373 ops/ms
Iteration   1: 9.286 ops/ms
Iteration   2: 9.308 ops/ms
Iteration   3: 9.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.270 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (9.217, 9.270, 9.308), stdev = 0.047
  CI (99.9%): [8.407, 10.134] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ops/ms
# Warmup Iteration   2: 8.834 ops/ms
# Warmup Iteration   3: 9.541 ops/ms
Iteration   1: 9.525 ops/ms
Iteration   2: 9.544 ops/ms
Iteration   3: 9.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.575 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (9.525, 9.575, 9.657), stdev = 0.071
  CI (99.9%): [8.278, 10.873] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 8.504 ops/ms
# Warmup Iteration   3: 9.098 ops/ms
Iteration   1: 9.352 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.258 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (9.161, 9.258, 9.352), stdev = 0.096
  CI (99.9%): [7.515, 11.001] (assumes normal distribution)


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
# Warmup Iteration   1: 2.723 ops/ms
# Warmup Iteration   2: 6.986 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 7.639 ops/ms
Iteration   2: 7.587 ops/ms
Iteration   3: 7.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.599 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (7.572, 7.599, 7.639), stdev = 0.035
  CI (99.9%): [6.961, 8.237] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.346 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.007 ms/op
Iteration   1: 3.595 ±(99.9%) 0.006 ms/op
Iteration   2: 3.419 ±(99.9%) 0.005 ms/op
Iteration   3: 3.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.509 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (3.419, 3.509, 3.595), stdev = 0.088
  CI (99.9%): [1.900, 5.118] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.849 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.004 ms/op
Iteration   1: 3.309 ±(99.9%) 0.004 ms/op
Iteration   2: 3.249 ±(99.9%) 0.005 ms/op
Iteration   3: 3.271 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.276 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.249, 3.276, 3.309), stdev = 0.030
  CI (99.9%): [2.723, 3.829] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.721 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.002 ms/op
Iteration   1: 3.481 ±(99.9%) 0.005 ms/op
Iteration   2: 3.504 ±(99.9%) 0.005 ms/op
Iteration   3: 3.611 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.532 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (3.481, 3.532, 3.611), stdev = 0.070
  CI (99.9%): [2.261, 4.803] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.248 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.005 ms/op
Iteration   1: 4.120 ±(99.9%) 0.006 ms/op
Iteration   2: 4.185 ±(99.9%) 0.008 ms/op
Iteration   3: 4.189 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.165 ±(99.9%) 0.710 ms/op [Average]
  (min, avg, max) = (4.120, 4.165, 4.189), stdev = 0.039
  CI (99.9%): [3.454, 4.875] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.930 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.010 ms/op
Iteration   1: 3.416 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  20.026 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  13.275 ms/op
                 createUser·p0.9999: 24.630 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  19.142 ms/op
                 createUser·p0.9999: 29.407 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277239
  mean =      3.461 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7648 
    [ 2.500,  5.000) = 264547 
    [ 5.000,  7.500) = 3833 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     14.873 ms/op
     p(99.9900) =     27.883 ms/op
     p(99.9990) =     30.056 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 8.213 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.009 ms/op
Iteration   1: 3.407 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  12.756 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  13.797 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  16.935 ms/op
                 existUser·p0.9999: 25.899 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287887
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4515 
    [ 2.500,  5.000) = 278078 
    [ 5.000,  7.500) = 4045 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     13.551 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.309 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 10.357 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.011 ms/op
Iteration   1: 3.520 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  18.941 ms/op
                 getUser·p0.9999: 21.919 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.165 ms/op
                 getUser·p0.999:  22.305 ms/op
                 getUser·p0.9999: 24.957 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.373 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  12.340 ms/op
                 getUser·p0.9999: 26.602 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275426
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7719 
    [ 2.500,  5.000) = 260839 
    [ 5.000,  7.500) = 5270 
    [ 7.500, 10.000) = 1014 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     25.246 ms/op
     p(99.9990) =     27.631 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 10.802 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.014 ms/op
Iteration   1: 4.195 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.646 ms/op
                 listUser·p0.999:  19.851 ms/op
                 listUser·p0.9999: 24.081 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 4.170 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 17.312 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 4.102 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 16.355 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230865
  mean =      4.156 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 222498 
    [ 5.000,  7.500) = 6535 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     22.244 ms/op
     p(99.9990) =     26.199 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.270 ± 0.864  ops/ms
ClientPb.existUser                       thrpt       3   9.575 ± 1.298  ops/ms
ClientPb.getUser                         thrpt       3   9.258 ± 1.743  ops/ms
ClientPb.listUser                        thrpt       3   7.599 ± 0.638  ops/ms
ClientPb.createUser                       avgt       3   3.509 ± 1.609   ms/op
ClientPb.existUser                        avgt       3   3.276 ± 0.553   ms/op
ClientPb.getUser                          avgt       3   3.532 ± 1.271   ms/op
ClientPb.listUser                         avgt       3   4.165 ± 0.710   ms/op
ClientPb.createUser                     sample  277239   3.461 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.346           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.873           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.883           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  287887   3.333 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.695           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.551           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.592           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  275426   3.486 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.373           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.390           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.246           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  230865   4.156 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.244           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444           ms/op
