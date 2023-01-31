# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.201 ops/ms
# Warmup Iteration   2: 5.729 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 9.260 ops/ms
Iteration   2: 9.481 ops/ms
Iteration   3: 8.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.231 ±(99.9%) 4.853 ops/ms [Average]
  (min, avg, max) = (8.951, 9.231, 9.481), stdev = 0.266
  CI (99.9%): [4.377, 14.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 8.494 ops/ms
# Warmup Iteration   3: 9.590 ops/ms
Iteration   1: 9.482 ops/ms
Iteration   2: 10.121 ops/ms
Iteration   3: 9.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.861 ±(99.9%) 6.124 ops/ms [Average]
  (min, avg, max) = (9.482, 9.861, 10.121), stdev = 0.336
  CI (99.9%): [3.738, 15.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.738 ops/ms
# Warmup Iteration   2: 8.241 ops/ms
# Warmup Iteration   3: 9.214 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.680 ops/ms
Iteration   3: 9.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.587 ±(99.9%) 2.638 ops/ms [Average]
  (min, avg, max) = (9.421, 9.587, 9.680), stdev = 0.145
  CI (99.9%): [6.949, 12.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.879 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 7.943 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 8.193 ops/ms
Iteration   3: 8.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.005 ±(99.9%) 3.603 ops/ms [Average]
  (min, avg, max) = (7.799, 8.005, 8.193), stdev = 0.197
  CI (99.9%): [4.402, 11.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.685 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.007 ms/op
Iteration   1: 3.378 ±(99.9%) 0.006 ms/op
Iteration   2: 3.338 ±(99.9%) 0.011 ms/op
Iteration   3: 3.490 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.402 ±(99.9%) 1.441 ms/op [Average]
  (min, avg, max) = (3.338, 3.402, 3.490), stdev = 0.079
  CI (99.9%): [1.961, 4.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.586 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.006 ms/op
Iteration   1: 3.299 ±(99.9%) 0.007 ms/op
Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
Iteration   3: 3.313 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.276 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (3.217, 3.276, 3.313), stdev = 0.052
  CI (99.9%): [2.324, 4.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.093 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.005 ms/op
Iteration   1: 3.483 ±(99.9%) 0.006 ms/op
Iteration   2: 3.594 ±(99.9%) 0.006 ms/op
Iteration   3: 3.506 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.528 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.483, 3.528, 3.594), stdev = 0.059
  CI (99.9%): [2.454, 4.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.478 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.944 ±(99.9%) 0.008 ms/op
Iteration   2: 3.903 ±(99.9%) 0.013 ms/op
Iteration   3: 3.906 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.918 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.903, 3.918, 3.944), stdev = 0.023
  CI (99.9%): [3.499, 4.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.509 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.011 ms/op
Iteration   1: 3.351 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.869 ms/op
                 createUser·p0.999:  21.481 ms/op
                 createUser·p0.9999: 27.817 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 3.636 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  23.591 ms/op
                 createUser·p0.9999: 25.696 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  16.559 ms/op
                 createUser·p0.9999: 26.805 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279192
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9449 
    [ 2.500,  5.000) = 261378 
    [ 5.000,  7.500) = 7167 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     28.149 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  14.675 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.273 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  13.455 ms/op
                 existUser·p0.9999: 25.796 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.743 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 32.781 ms/op
                 existUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291292
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13715 
    [ 2.500,  5.000) = 272206 
    [ 5.000,  7.500) = 4372 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.233 ms/op
     p(99.9900) =     30.420 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 10.660 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.012 ms/op
Iteration   1: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  20.776 ms/op
                 getUser·p0.9999: 22.944 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  19.943 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.394 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.927 ms/op
                 getUser·p0.999:  21.229 ms/op
                 getUser·p0.9999: 28.017 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284430
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6430 
    [ 2.500,  5.000) = 271385 
    [ 5.000,  7.500) = 5599 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     20.826 ms/op
     p(99.9900) =     26.742 ms/op
     p(99.9990) =     28.317 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.926 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.014 ms/op
Iteration   1: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  21.660 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 18.748 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 4.026 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 17.736 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238317
  mean =      4.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 229916 
    [ 5.000,  7.500) = 6098 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     22.714 ms/op
     p(99.9990) =     23.838 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.231 ± 4.853  ops/ms
ClientPb.existUser                       thrpt       3   9.861 ± 6.124  ops/ms
ClientPb.getUser                         thrpt       3   9.587 ± 2.638  ops/ms
ClientPb.listUser                        thrpt       3   8.005 ± 3.603  ops/ms
ClientPb.createUser                       avgt       3   3.402 ± 1.441   ms/op
ClientPb.existUser                        avgt       3   3.276 ± 0.953   ms/op
ClientPb.getUser                          avgt       3   3.528 ± 1.073   ms/op
ClientPb.listUser                         avgt       3   3.918 ± 0.419   ms/op
ClientPb.createUser                     sample  279192   3.438 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.393           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.968           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.312           ms/op
ClientPb.existUser                      sample  291292   3.296 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.397           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.233           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.420           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.423           ms/op
ClientPb.getUser                        sample  284430   3.372 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.552           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.742           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  238317   4.029 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.236           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.714           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.019           ms/op
