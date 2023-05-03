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
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 5.048 ops/ms
# Warmup Iteration   3: 8.370 ops/ms
Iteration   1: 9.201 ops/ms
Iteration   2: 9.530 ops/ms
Iteration   3: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.353 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (9.201, 9.353, 9.530), stdev = 0.166
  CI (99.9%): [6.330, 12.376] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ops/ms
# Warmup Iteration   2: 8.747 ops/ms
# Warmup Iteration   3: 9.487 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 9.877 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.872 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (9.766, 9.872, 9.972), stdev = 0.103
  CI (99.9%): [7.994, 11.750] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.873 ops/ms
# Warmup Iteration   2: 8.219 ops/ms
# Warmup Iteration   3: 9.393 ops/ms
Iteration   1: 9.103 ops/ms
Iteration   2: 9.274 ops/ms
Iteration   3: 9.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.237 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (9.103, 9.237, 9.334), stdev = 0.120
  CI (99.9%): [7.053, 11.420] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 6.831 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 7.875 ops/ms
Iteration   2: 7.932 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.936 ±(99.9%) 1.153 ops/ms [Average]
  (min, avg, max) = (7.875, 7.936, 8.001), stdev = 0.063
  CI (99.9%): [6.783, 9.089] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.584 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.004 ms/op
Iteration   1: 3.394 ±(99.9%) 0.008 ms/op
Iteration   2: 3.439 ±(99.9%) 0.005 ms/op
Iteration   3: 3.266 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.366 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (3.266, 3.366, 3.439), stdev = 0.089
  CI (99.9%): [1.734, 4.999] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.447 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.004 ms/op
Iteration   1: 3.262 ±(99.9%) 0.004 ms/op
Iteration   2: 3.288 ±(99.9%) 0.004 ms/op
Iteration   3: 3.244 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.265 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.244, 3.265, 3.288), stdev = 0.022
  CI (99.9%): [2.855, 3.675] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.471 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.005 ms/op
Iteration   1: 3.334 ±(99.9%) 0.006 ms/op
Iteration   2: 3.423 ±(99.9%) 0.006 ms/op
Iteration   3: 3.334 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.364 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.334, 3.364, 3.423), stdev = 0.052
  CI (99.9%): [2.421, 4.306] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.981 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.014 ms/op
Iteration   1: 4.101 ±(99.9%) 0.010 ms/op
Iteration   2: 4.041 ±(99.9%) 0.006 ms/op
Iteration   3: 3.806 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.983 ±(99.9%) 2.845 ms/op [Average]
  (min, avg, max) = (3.806, 3.983, 4.101), stdev = 0.156
  CI (99.9%): [1.138, 6.828] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.119 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.691 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  20.360 ms/op
                 createUser·p0.9999: 26.465 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   2: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  20.624 ms/op
                 createUser·p0.9999: 28.819 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  18.478 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275555
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13532 
    [ 2.500,  5.000) = 251634 
    [ 5.000,  7.500) = 8509 
    [ 7.500, 10.000) = 1367 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     18.922 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     29.310 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.898 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
Iteration   1: 3.288 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  10.508 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  20.217 ms/op
                 existUser·p0.9999: 23.205 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 3.337 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  22.751 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291280
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10941 
    [ 2.500,  5.000) = 275016 
    [ 5.000,  7.500) = 4223 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     12.677 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 10.121 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.011 ms/op
Iteration   1: 3.419 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 25.907 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   2: 3.394 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  21.630 ms/op
                 getUser·p0.9999: 25.788 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.447 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.345 ms/op
                 getUser·p0.999:  19.178 ms/op
                 getUser·p0.9999: 28.204 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280645
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6242 
    [ 2.500,  5.000) = 265191 
    [ 5.000,  7.500) = 7807 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     27.031 ms/op
     p(99.9990) =     28.875 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 11.441 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.014 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  19.178 ms/op
                 listUser·p0.9999: 26.210 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.024 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.662 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.890 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  14.555 ms/op
                 listUser·p0.9999: 17.659 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242418
  mean =      3.956 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 236321 
    [ 5.000,  7.500) = 4007 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     23.389 ms/op
     p(99.9990) =     27.307 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.353 ± 3.023  ops/ms
ClientPb.existUser                       thrpt       3   9.872 ± 1.878  ops/ms
ClientPb.getUser                         thrpt       3   9.237 ± 2.183  ops/ms
ClientPb.listUser                        thrpt       3   7.936 ± 1.153  ops/ms
ClientPb.createUser                       avgt       3   3.366 ± 1.633   ms/op
ClientPb.existUser                        avgt       3   3.265 ± 0.410   ms/op
ClientPb.getUser                          avgt       3   3.364 ± 0.943   ms/op
ClientPb.listUser                         avgt       3   3.983 ± 2.845   ms/op
ClientPb.createUser                     sample  275555   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.798           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.922           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.165           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.081           ms/op
ClientPb.existUser                      sample  291280   3.293 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.677           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.524           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  280645   3.420 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.742           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.031           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164           ms/op
ClientPb.listUser                       sample  242418   3.956 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
