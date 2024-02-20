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
# Warmup Iteration   1: 4.945 ops/ms
# Warmup Iteration   2: 12.077 ops/ms
# Warmup Iteration   3: 12.549 ops/ms
Iteration   1: 12.719 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 12.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.790 ±(99.9%) 1.131 ops/ms [Average]
  (min, avg, max) = (12.719, 12.790, 12.831), stdev = 0.062
  CI (99.9%): [11.659, 13.921] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ops/ms
# Warmup Iteration   2: 13.305 ops/ms
# Warmup Iteration   3: 13.292 ops/ms
Iteration   1: 13.271 ops/ms
Iteration   2: 13.435 ops/ms
Iteration   3: 13.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.329 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (13.271, 13.329, 13.435), stdev = 0.092
  CI (99.9%): [11.655, 15.004] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.382 ops/ms
# Warmup Iteration   2: 12.724 ops/ms
# Warmup Iteration   3: 12.908 ops/ms
Iteration   1: 12.917 ops/ms
Iteration   2: 12.941 ops/ms
Iteration   3: 12.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.889 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (12.809, 12.889, 12.941), stdev = 0.070
  CI (99.9%): [11.613, 14.165] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.013 ops/ms
# Warmup Iteration   2: 10.574 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.850 ops/ms
Iteration   2: 10.693 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.742 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (10.683, 10.742, 10.850), stdev = 0.094
  CI (99.9%): [9.032, 12.453] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.003 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (2.454, 2.488, 2.506), stdev = 0.029
  CI (99.9%): [1.954, 3.022] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.383 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.004 ms/op
Iteration   1: 2.392 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.386 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.400 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.386, 2.400, 2.422), stdev = 0.020
  CI (99.9%): [2.040, 2.760] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.003 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.453, 2.465, 2.486), stdev = 0.018
  CI (99.9%): [2.143, 2.787] (assumes normal distribution)


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
Iteration   3: 3.005 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.992, 3.008, 3.027), stdev = 0.017
  CI (99.9%): [2.689, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  10.082 ms/op
                 createUser·p0.9999: 13.391 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 12.536 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  8.286 ms/op
                 createUser·p0.9999: 10.474 ms/op
                 createUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383759
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 184534 
    [ 2.500,  3.750) = 195396 
    [ 3.750,  5.000) = 2842 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.982 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.953 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
Iteration   1: 2.406 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.236 ms/op
                 existUser·p0.999:  4.801 ms/op
                 existUser·p0.9999: 13.430 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.651 ms/op
                 existUser·p0.999:  9.192 ms/op
                 existUser·p0.9999: 18.154 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  8.306 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392891
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 192766 
    [ 2.500,  3.750) = 197353 
    [ 3.750,  5.000) = 2040 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      7.168 ms/op
     p(99.9900) =     13.769 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  6.012 ms/op
                 getUser·p0.9999: 13.927 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  6.151 ms/op
                 getUser·p0.9999: 13.421 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  5.952 ms/op
                 getUser·p0.9999: 10.076 ms/op
                 getUser·p1.00:   10.584 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389162
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 195869 
    [ 2.500,  3.750) = 190015 
    [ 3.750,  5.000) = 2591 
    [ 5.000,  6.250) = 206 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.076 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     14.634 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.450 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 11.743 ms/op
                 listUser·p1.00:   12.796 ms/op

Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.685 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 11.218 ms/op
                 listUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318974
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 93356 
    [ 2.500,  3.750) = 186986 
    [ 3.750,  5.000) = 31311 
    [ 5.000,  6.250) = 5880 
    [ 6.250,  7.500) = 670 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     11.626 ms/op
     p(99.9990) =     13.344 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.790 ± 1.131  ops/ms
ClientPb.existUser                       thrpt       3  13.329 ± 1.674  ops/ms
ClientPb.getUser                         thrpt       3  12.889 ± 1.276  ops/ms
ClientPb.listUser                        thrpt       3  10.742 ± 1.710  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.534   ms/op
ClientPb.existUser                        avgt       3   2.400 ± 0.360   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.319   ms/op
ClientPb.createUser                     sample  383759   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.861           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  392891   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.914           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.168           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.769           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.514           ms/op
ClientPb.getUser                        sample  389162   2.465 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.814           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.697           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.762           ms/op
ClientPb.listUser                       sample  318974   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.685           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.626           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
