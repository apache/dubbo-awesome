# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.901 ops/ms
# Warmup Iteration   2: 4.698 ops/ms
# Warmup Iteration   3: 8.116 ops/ms
Iteration   1: 8.952 ops/ms
Iteration   2: 9.073 ops/ms
Iteration   3: 8.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.951 ±(99.9%) 2.243 ops/ms [Average]
  (min, avg, max) = (8.827, 8.951, 9.073), stdev = 0.123
  CI (99.9%): [6.708, 11.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.648 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.176 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.233 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (9.176, 9.233, 9.284), stdev = 0.054
  CI (99.9%): [8.248, 10.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.439 ops/ms
# Warmup Iteration   2: 7.668 ops/ms
# Warmup Iteration   3: 8.724 ops/ms
Iteration   1: 8.660 ops/ms
Iteration   2: 8.767 ops/ms
Iteration   3: 9.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.845 ±(99.9%) 4.264 ops/ms [Average]
  (min, avg, max) = (8.660, 8.845, 9.108), stdev = 0.234
  CI (99.9%): [4.582, 13.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.487 ops/ms
# Warmup Iteration   2: 6.633 ops/ms
# Warmup Iteration   3: 7.450 ops/ms
Iteration   1: 7.463 ops/ms
Iteration   2: 7.427 ops/ms
Iteration   3: 7.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.417 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (7.361, 7.417, 7.463), stdev = 0.051
  CI (99.9%): [6.481, 8.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.879 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.003 ms/op
Iteration   1: 3.630 ±(99.9%) 0.005 ms/op
Iteration   2: 3.575 ±(99.9%) 0.005 ms/op
Iteration   3: 3.582 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.596 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.575, 3.596, 3.630), stdev = 0.030
  CI (99.9%): [3.045, 4.146] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.210 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.005 ms/op
Iteration   1: 3.425 ±(99.9%) 0.003 ms/op
Iteration   2: 3.456 ±(99.9%) 0.005 ms/op
Iteration   3: 3.356 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.413 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.356, 3.413, 3.456), stdev = 0.051
  CI (99.9%): [2.476, 4.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.058 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.004 ms/op
Iteration   1: 3.535 ±(99.9%) 0.006 ms/op
Iteration   2: 3.576 ±(99.9%) 0.004 ms/op
Iteration   3: 3.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.546 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (3.526, 3.546, 3.576), stdev = 0.026
  CI (99.9%): [3.063, 4.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.116 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.006 ms/op
Iteration   1: 4.288 ±(99.9%) 0.005 ms/op
Iteration   2: 4.168 ±(99.9%) 0.007 ms/op
Iteration   3: 4.177 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.211 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (4.168, 4.211, 4.288), stdev = 0.067
  CI (99.9%): [2.996, 5.426] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.822 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.011 ms/op
Iteration   1: 3.605 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  21.112 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   2: 3.582 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  22.708 ms/op
                 createUser·p0.9999: 25.889 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 26.637 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269035
  mean =      3.567 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3348 
    [ 2.500,  5.000) = 258156 
    [ 5.000,  7.500) = 6305 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     25.926 ms/op
     p(99.9990) =     27.316 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.463 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
Iteration   1: 3.523 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  20.971 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.424 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.786 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 26.651 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  23.597 ms/op
                 existUser·p0.9999: 30.929 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274717
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10610 
    [ 2.500,  5.000) = 257426 
    [ 5.000,  7.500) = 5139 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     28.681 ms/op
     p(99.9990) =     31.269 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.701 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.013 ms/op
Iteration   1: 3.508 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  22.671 ms/op
                 getUser·p0.9999: 31.565 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   2: 3.591 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  23.167 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  20.335 ms/op
                 getUser·p0.9999: 28.312 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269771
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3500 
    [ 2.500,  5.000) = 258754 
    [ 5.000,  7.500) = 5849 
    [ 7.500, 10.000) = 1043 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     21.249 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     34.361 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.372 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.013 ms/op
Iteration   1: 4.252 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 22.658 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.197 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 4.174 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.089 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228207
  mean =      4.208 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 219046 
    [ 5.000,  7.500) = 6717 
    [ 7.500, 10.000) = 1559 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     22.082 ms/op
     p(99.9990) =     23.665 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.951 ± 2.243  ops/ms
ClientPb.existUser                       thrpt       3   9.233 ± 0.986  ops/ms
ClientPb.getUser                         thrpt       3   8.845 ± 4.264  ops/ms
ClientPb.listUser                        thrpt       3   7.417 ± 0.936  ops/ms
ClientPb.createUser                       avgt       3   3.596 ± 0.551   ms/op
ClientPb.existUser                        avgt       3   3.413 ± 0.936   ms/op
ClientPb.getUser                          avgt       3   3.546 ± 0.483   ms/op
ClientPb.listUser                         avgt       3   4.211 ± 1.215   ms/op
ClientPb.createUser                     sample  269035   3.567 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.622           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.874           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.926           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.722           ms/op
ClientPb.existUser                      sample  274717   3.493 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.681           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  269771   3.558 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.249           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.312           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  228207   4.208 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.518           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.082           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.150           ms/op
