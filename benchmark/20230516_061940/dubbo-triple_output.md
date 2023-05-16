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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 6.155 ops/ms
# Warmup Iteration   3: 8.430 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.319 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.326 ±(99.9%) 0.267 ops/ms [Average]
  (min, avg, max) = (9.318, 9.326, 9.343), stdev = 0.015
  CI (99.9%): [9.060, 9.593] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 9.120 ops/ms
# Warmup Iteration   3: 9.710 ops/ms
Iteration   1: 9.898 ops/ms
Iteration   2: 9.709 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.679 ±(99.9%) 4.296 ops/ms [Average]
  (min, avg, max) = (9.430, 9.679, 9.898), stdev = 0.235
  CI (99.9%): [5.383, 13.974] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.099 ops/ms
# Warmup Iteration   2: 8.392 ops/ms
# Warmup Iteration   3: 9.415 ops/ms
Iteration   1: 9.546 ops/ms
Iteration   2: 9.633 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.628 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (9.546, 9.628, 9.704), stdev = 0.079
  CI (99.9%): [8.184, 11.072] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.964 ops/ms
# Warmup Iteration   2: 7.652 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 7.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.085 ±(99.9%) 2.934 ops/ms [Average]
  (min, avg, max) = (7.900, 8.085, 8.195), stdev = 0.161
  CI (99.9%): [5.151, 11.019] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.823 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.009 ms/op
Iteration   1: 3.526 ±(99.9%) 0.009 ms/op
Iteration   2: 3.352 ±(99.9%) 0.006 ms/op
Iteration   3: 3.359 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.412 ±(99.9%) 1.799 ms/op [Average]
  (min, avg, max) = (3.352, 3.412, 3.526), stdev = 0.099
  CI (99.9%): [1.613, 5.211] (assumes normal distribution)


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
# Warmup Iteration   1: 8.128 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.003 ms/op
Iteration   1: 3.215 ±(99.9%) 0.003 ms/op
Iteration   2: 3.269 ±(99.9%) 0.010 ms/op
Iteration   3: 3.271 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.252 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.215, 3.252, 3.271), stdev = 0.032
  CI (99.9%): [2.669, 3.834] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.788 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.005 ms/op
Iteration   1: 3.423 ±(99.9%) 0.004 ms/op
Iteration   2: 3.350 ±(99.9%) 0.005 ms/op
Iteration   3: 3.347 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.373 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.347, 3.373, 3.423), stdev = 0.043
  CI (99.9%): [2.587, 4.159] (assumes normal distribution)


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
# Warmup Iteration   1: 9.674 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.010 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
Iteration   3: 3.768 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.861 ±(99.9%) 1.619 ms/op [Average]
  (min, avg, max) = (3.768, 3.861, 3.944), stdev = 0.089
  CI (99.9%): [2.243, 5.480] (assumes normal distribution)


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
# Warmup Iteration   1: 9.684 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.012 ms/op
Iteration   1: 3.390 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  21.223 ms/op
                 createUser·p0.9999: 34.109 ms/op
                 createUser·p1.00:   35.258 ms/op

Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 29.178 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282572
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9628 
    [ 2.500,  5.000) = 267948 
    [ 5.000,  7.500) = 3809 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     21.018 ms/op
     p(99.9900) =     32.530 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 8.614 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
Iteration   1: 3.221 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.186 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  14.269 ms/op
                 existUser·p0.9999: 25.075 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  9.586 ms/op
                 existUser·p0.9999: 26.748 ms/op
                 existUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294281
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12332 
    [ 2.500,  5.000) = 275656 
    [ 5.000,  7.500) = 5305 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     13.742 ms/op
     p(99.9900) =     26.692 ms/op
     p(99.9990) =     28.425 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 9.170 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  20.113 ms/op
                 getUser·p0.9999: 22.498 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  22.417 ms/op
                 getUser·p0.9999: 25.812 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.556 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 24.052 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278327
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12729 
    [ 2.500,  5.000) = 257737 
    [ 5.000,  7.500) = 7101 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.407 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 9.646 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.014 ms/op
Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  19.036 ms/op
                 listUser·p0.9999: 27.591 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 4.100 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.130 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 24.484 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 3.812 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241829
  mean =      3.966 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 232690 
    [ 5.000,  7.500) = 6261 
    [ 7.500, 10.000) = 2061 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     25.940 ms/op
     p(99.9990) =     28.153 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.326 ± 0.267  ops/ms
ClientPb.existUser                       thrpt       3   9.679 ± 4.296  ops/ms
ClientPb.getUser                         thrpt       3   9.628 ± 1.444  ops/ms
ClientPb.listUser                        thrpt       3   8.085 ± 2.934  ops/ms
ClientPb.createUser                       avgt       3   3.412 ± 1.799   ms/op
ClientPb.existUser                        avgt       3   3.252 ± 0.582   ms/op
ClientPb.getUser                          avgt       3   3.373 ± 0.786   ms/op
ClientPb.listUser                         avgt       3   3.861 ± 1.619   ms/op
ClientPb.createUser                     sample  282572   3.399 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.151           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.018           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.530           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  294281   3.262 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.742           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.738           ms/op
ClientPb.getUser                        sample  278327   3.449 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.551           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.478           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.870           ms/op
ClientPb.listUser                       sample  241829   3.966 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.741           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.940           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.901           ms/op
