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
# Warmup Iteration   1: 1.976 ops/ms
# Warmup Iteration   2: 5.402 ops/ms
# Warmup Iteration   3: 8.314 ops/ms
Iteration   1: 9.355 ops/ms
Iteration   2: 9.476 ops/ms
Iteration   3: 9.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.383 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (9.319, 9.383, 9.476), stdev = 0.082
  CI (99.9%): [7.879, 10.887] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.203 ops/ms
# Warmup Iteration   2: 8.773 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.882 ops/ms
Iteration   2: 9.759 ops/ms
Iteration   3: 9.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.734 ±(99.9%) 2.968 ops/ms [Average]
  (min, avg, max) = (9.559, 9.734, 9.882), stdev = 0.163
  CI (99.9%): [6.765, 12.702] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.958 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 9.176 ops/ms
Iteration   1: 9.526 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 9.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.558 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (9.526, 9.558, 9.591), stdev = 0.032
  CI (99.9%): [8.966, 10.149] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 7.318 ops/ms
# Warmup Iteration   3: 7.969 ops/ms
Iteration   1: 7.833 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.046 ±(99.9%) 3.682 ops/ms [Average]
  (min, avg, max) = (7.833, 8.046, 8.234), stdev = 0.202
  CI (99.9%): [4.365, 11.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.561 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.003 ms/op
Iteration   1: 3.494 ±(99.9%) 0.003 ms/op
Iteration   2: 3.614 ±(99.9%) 0.004 ms/op
Iteration   3: 3.525 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.544 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.494, 3.544, 3.614), stdev = 0.062
  CI (99.9%): [2.410, 4.679] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 10.509 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.006 ms/op
Iteration   1: 3.340 ±(99.9%) 0.007 ms/op
Iteration   2: 3.334 ±(99.9%) 0.007 ms/op
Iteration   3: 3.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.385 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (3.334, 3.385, 3.482), stdev = 0.084
  CI (99.9%): [1.861, 4.910] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.881 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.007 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
Iteration   2: 3.402 ±(99.9%) 0.008 ms/op
Iteration   3: 3.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.434 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.402, 3.434, 3.478), stdev = 0.039
  CI (99.9%): [2.718, 4.151] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.608 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.009 ms/op
Iteration   1: 4.006 ±(99.9%) 0.013 ms/op
Iteration   2: 4.090 ±(99.9%) 0.005 ms/op
Iteration   3: 3.914 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.003 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (3.914, 4.003, 4.090), stdev = 0.088
  CI (99.9%): [2.400, 5.607] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 11.012 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.013 ms/op
Iteration   1: 3.418 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  20.987 ms/op
                 createUser·p0.9999: 24.291 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  24.334 ms/op
                 createUser·p0.9999: 27.475 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  21.356 ms/op
                 createUser·p0.9999: 29.386 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280805
  mean =      3.416 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8591 
    [ 2.500,  5.000) = 266225 
    [ 5.000,  7.500) = 4994 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     28.145 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.640 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
Iteration   1: 3.302 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.450 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 30.933 ms/op
                 existUser·p1.00:   31.523 ms/op

Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 27.432 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295448
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9212 
    [ 2.500,  5.000) = 280967 
    [ 5.000,  7.500) = 4421 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     29.572 ms/op
     p(99.9990) =     31.271 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.771 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.011 ms/op
Iteration   1: 3.622 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  21.399 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   2: 3.578 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 27.789 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.472 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.448 ms/op
                 getUser·p0.999:  23.918 ms/op
                 getUser·p0.9999: 39.846 ms/op
                 getUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269869
  mean =      3.556 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 260263 
    [ 5.000, 10.000) = 9176 
    [10.000, 15.000) = 113 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 114 
    [25.000, 30.000) = 135 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     21.832 ms/op
     p(99.9900) =     38.536 ms/op
     p(99.9990) =     40.344 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.287 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  23.216 ms/op
                 listUser·p0.9999: 31.195 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 4.015 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.847 ms/op
                 listUser·p0.9999: 19.761 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.229 ms/op
                 listUser·p0.9999: 18.349 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237786
  mean =      4.036 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 230027 
    [ 5.000,  7.500) = 5580 
    [ 7.500, 10.000) = 1268 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     30.376 ms/op
     p(99.9990) =     31.228 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.383 ± 1.504  ops/ms
ClientPb.existUser                       thrpt       3   9.734 ± 2.968  ops/ms
ClientPb.getUser                         thrpt       3   9.558 ± 0.591  ops/ms
ClientPb.listUser                        thrpt       3   8.046 ± 3.682  ops/ms
ClientPb.createUser                       avgt       3   3.544 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.385 ± 1.525   ms/op
ClientPb.getUser                          avgt       3   3.434 ± 0.716   ms/op
ClientPb.listUser                         avgt       3   4.003 ± 1.603   ms/op
ClientPb.createUser                     sample  280805   3.416 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.037           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.145           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.852           ms/op
ClientPb.existUser                      sample  295448   3.249 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.572           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  269869   3.556 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.210           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.832           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.536           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.698           ms/op
ClientPb.listUser                       sample  237786   4.036 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.563           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.236           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.376           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
