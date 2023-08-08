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
# Warmup Iteration   1: 2.025 ops/ms
# Warmup Iteration   2: 5.334 ops/ms
# Warmup Iteration   3: 8.622 ops/ms
Iteration   1: 9.229 ops/ms
Iteration   2: 9.412 ops/ms
Iteration   3: 9.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.342 ±(99.9%) 1.812 ops/ms [Average]
  (min, avg, max) = (9.229, 9.342, 9.412), stdev = 0.099
  CI (99.9%): [7.530, 11.154] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 8.300 ops/ms
# Warmup Iteration   3: 9.616 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 9.489 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.507 ±(99.9%) 4.727 ops/ms [Average]
  (min, avg, max) = (9.257, 9.507, 9.774), stdev = 0.259
  CI (99.9%): [4.780, 14.234] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 8.377 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.207 ops/ms
Iteration   2: 9.305 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.260 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (9.207, 9.260, 9.305), stdev = 0.050
  CI (99.9%): [8.357, 10.163] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.553 ops/ms
# Warmup Iteration   2: 6.900 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 7.687 ops/ms
Iteration   2: 7.893 ops/ms
Iteration   3: 8.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.882 ±(99.9%) 3.475 ops/ms [Average]
  (min, avg, max) = (7.687, 7.882, 8.067), stdev = 0.190
  CI (99.9%): [4.407, 11.357] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.673 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.005 ms/op
Iteration   1: 3.408 ±(99.9%) 0.011 ms/op
Iteration   2: 3.458 ±(99.9%) 0.005 ms/op
Iteration   3: 3.486 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.451 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.408, 3.451, 3.486), stdev = 0.039
  CI (99.9%): [2.734, 4.168] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.357 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.009 ms/op
Iteration   1: 3.472 ±(99.9%) 0.006 ms/op
Iteration   2: 3.397 ±(99.9%) 0.007 ms/op
Iteration   3: 3.401 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.423 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.397, 3.423, 3.472), stdev = 0.043
  CI (99.9%): [2.647, 4.200] (assumes normal distribution)


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
# Warmup Iteration   1: 9.856 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.004 ms/op
Iteration   1: 3.448 ±(99.9%) 0.002 ms/op
Iteration   2: 3.440 ±(99.9%) 0.005 ms/op
Iteration   3: 3.586 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.491 ±(99.9%) 1.494 ms/op [Average]
  (min, avg, max) = (3.440, 3.491, 3.586), stdev = 0.082
  CI (99.9%): [1.997, 4.986] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.513 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.662 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.265 ±(99.9%) 0.007 ms/op
Iteration   1: 4.061 ±(99.9%) 0.008 ms/op
Iteration   2: 4.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.989 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.049 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.989, 4.049, 4.098), stdev = 0.055
  CI (99.9%): [3.043, 5.056] (assumes normal distribution)


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
# Warmup Iteration   1: 9.226 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
Iteration   1: 3.445 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  19.484 ms/op
                 createUser·p0.9999: 22.708 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.591 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.354 ms/op
                 createUser·p0.999:  20.905 ms/op
                 createUser·p0.9999: 29.176 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.445 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.183 ms/op
                 createUser·p0.999:  20.039 ms/op
                 createUser·p0.9999: 32.718 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274613
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11544 
    [ 2.500,  5.000) = 254637 
    [ 5.000,  7.500) = 6930 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.430 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     29.985 ms/op
     p(99.9990) =     33.688 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.889 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  12.865 ms/op
                 existUser·p0.9999: 23.462 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   2: 3.385 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  23.242 ms/op
                 existUser·p0.9999: 30.561 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 3.388 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  11.908 ms/op
                 existUser·p0.9999: 31.710 ms/op
                 existUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286684
  mean =      3.347 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8735 
    [ 2.500,  5.000) = 268525 
    [ 5.000,  7.500) = 8078 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     30.846 ms/op
     p(99.9990) =     32.060 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 9.287 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.013 ms/op
Iteration   1: 3.559 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  10.650 ms/op
                 getUser·p0.9999: 24.184 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.471 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  23.253 ms/op
                 getUser·p0.9999: 26.599 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.534 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.345 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 31.588 ms/op
                 getUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272654
  mean =      3.521 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7757 
    [ 2.500,  5.000) = 254612 
    [ 5.000,  7.500) = 8631 
    [ 7.500, 10.000) = 1074 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.933 ms/op
     p(99.9900) =     28.893 ms/op
     p(99.9990) =     31.925 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 10.434 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.015 ms/op
Iteration   1: 4.058 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.903 ms/op
                 listUser·p0.999:  22.027 ms/op
                 listUser·p0.9999: 26.120 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 30.802 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237547
  mean =      4.039 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 227673 
    [ 5.000,  7.500) = 6792 
    [ 7.500, 10.000) = 2017 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.901 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     17.284 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.342 ± 1.812  ops/ms
ClientPb.existUser                       thrpt       3   9.507 ± 4.727  ops/ms
ClientPb.getUser                         thrpt       3   9.260 ± 0.903  ops/ms
ClientPb.listUser                        thrpt       3   7.882 ± 3.475  ops/ms
ClientPb.createUser                       avgt       3   3.451 ± 0.717   ms/op
ClientPb.existUser                        avgt       3   3.423 ± 0.777   ms/op
ClientPb.getUser                          avgt       3   3.491 ± 1.494   ms/op
ClientPb.listUser                         avgt       3   4.049 ± 1.007   ms/op
ClientPb.createUser                     sample  274613   3.492 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.908           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.430           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.988           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.985           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  286684   3.347 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.648           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.846           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.506           ms/op
ClientPb.getUser                        sample  272654   3.521 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.345           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.933           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.893           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  237547   4.039 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.284           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.575           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.195           ms/op
